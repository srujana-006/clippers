This section contains the schematic file and simulation parameters for a "two level voltage clipper circuit". 
The application of such a circuit would be to convert sine waves into square waves for digital signals.
In many instances, the oscillators used generate sine wave where as the logical operations require pulses and sqaures.
The working of the circuit is simple: 
Both the diodes will be in off state when the input voltage is between the two desired voltage levels.
When voltage exceeds one of the two levels, the diode in that branch stays on, and reflects the voltage of that branch.
This is a demonstration of the same implemented in LTSpice.
