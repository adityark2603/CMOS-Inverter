# CMOS-Inverter
A CMOS Inverter implemented in Cadence Virtuoso tool

A CMOS inverter is a fundamental logic gate in digital circuits, built using a p-channel (PMOS) and an n-channel (NMOS) MOSFET in a complementary configuration. It functions as a NOT gate, inverting the input signal:

Input = High (1) → NMOS conducts, PMOS is off → Output = Low (0)
Input = Low (0) → PMOS conducts, NMOS is off → Output = High (1)

In this project, the specifications I've used are:
(i) 90 nm technology (gpdk90 library)
(ii) Vdc = 1.2V

Rest all were specific to the analysis done, either DC analysis or Transient analysis
