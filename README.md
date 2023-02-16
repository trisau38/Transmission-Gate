# Transmission-Gate
A transmission gate, or analog switch, is defined as an electronic element that will selectively
block or pass a signal level from the input to the output. This solid-state switch is comprised
of a pMOS transistor and nMOS transistor. The control gates are biased in a complementary
manner so that both transistors are either on or off.

When the voltage on node A is a Logic 1, the complementary Logic 0 is applied to node active-
low A, allowing both transistors to conduct and pass the signal at IN to OUT. When the voltage
on node active-low A is a Logic 0, the complementary Logic 1 is applied to node A, turning
both transistors off and forcing a high-impedance condition on both the IN and OUT nodes.
Boolean expression: Y = A

## Circuit Diagram:
![tr_cir](https://user-images.githubusercontent.com/108890713/219368788-cb21f418-ab18-4a69-a2e3-2a31881f443d.jpeg)

## Euler's Path:
![tr_euler](https://user-images.githubusercontent.com/108890713/219368887-fb6f5b01-73df-4ce2-b788-3abd32e21062.jpeg)

## Stick Diagram:
![tr_stick](https://user-images.githubusercontent.com/108890713/219368964-24d0aecc-03fa-4ea6-8db2-ef284865ecf6.jpeg)

## Magic Layout:
![tr_mag](https://user-images.githubusercontent.com/108890713/219369035-92ce8dc8-e7fb-40aa-a4d0-daba7bc18557.png)

## AC Analysis Output:
![tr_out](https://user-images.githubusercontent.com/108890713/219369112-518d222e-d54d-4744-81f2-48c9a59fddf0.png)

## Calculations:
Wp to Wn ratio(W p/W n) = 3 (Taken for the simulation)
rise time = 2.0ns
fall time = 2.0ns
Here, rise time and fall time come out to nearly be the same.

## Observation:
It is observed that the output acts like a buffer for the given input. The rise and fall times
obtained are also almost equal.
