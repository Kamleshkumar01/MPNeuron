# MP Neuron and Logic Gates

This repository contains a Python implementation of the McCulloch-Pitts neuron (MP Neuron) and basic logic gates using the MP Neuron model. The MP Neuron is a simplified model of a biological neuron, and the implemented logic gates include AND, OR, and NOT gates.

# MPNeuron Class

The MPNeuron class is designed to represent an MP Neuron with customizable weights and a threshold. It includes a method, activate, which calculates the output based on the weighted sum of inputs and the specified threshold.

# Logic Gates

Instances of the MPNeuron class are used to create AND, OR, and NOT gates. The weights and thresholds are set according to the logic gate's behavior.

# Testing

The test_gate function is utilized to test the behavior of each gate for different input combinations, providing clear examples of how the gates operate.

# Usage Example

# python

# AND gate
and_gate = MPNeuron(weights=[1, 1], threshold=2)

# OR gate
or_gate = MPNeuron(weights=[1, 1], threshold=1)

# NOT gate
not_gate = MPNeuron(weights=[-1], threshold=0)

# Test the gates
test_gate(and_gate, [0, 0])

test_gate(and_gate, [0, 1])

test_gate(and_gate, [1, 0])

test_gate(and_gate, [1, 1])



test_gate(or_gate, [0, 0])

test_gate(or_gate, [0, 1])

test_gate(or_gate, [1, 0])

test_gate(or_gate, [1, 1])



test_gate(not_gate, [0])

test_gate(not_gate, [1])

Feel free to adjust the description according to the specific details and purpose of your code. Additionally, you might want to include information about dependencies, usage instructions, or any other relevant details that could help users understand and use your code effectively.
