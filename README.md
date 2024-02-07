# Study for Design of Noise and Process Variation Tolerant, Low-Power, High-Speed, and Low-Energy Full Adders in CNFET Technology

## VLSI Analog Design, Layout Design, Reaserch Paper Study

Findings: In this paper, a number of novel 1-bit full adder cells using carbon nanotube field-effect
transistor devices are presented.
First of all, some two-input XOR/XNOR circuits are proposed, and then, they are
employed to form 1-bit full adders.
Totally, five full adders with driving power and one without driving power are proposed
in this paper, each of which has its own merits.
In this project main focus is on reducing the power consumption of the circuit and
increasing its performance.
Different full adder circuits are being compared based on their power delay and energy
delay products.
Simulations with regard to supply power scaling and different load conditions confirm
the superiority of the proposed cells compared with the previously reported ones in
terms of power, delay, power-delay product (PDP), and Energy delay product (EDP).
Also embedding the proposed full adders in the large circuits, such as ripple carry adder
(RCA), with a wide word length shows that they have better power, speed, and PDP
with regard to their counterparts.
Furthermore, the susceptibility of the full adders against both input noise and process
variations (diameter deviations of carbon nanotubes) is studied.

## Adder Design 

Our proposed full adder cell is based on the following logic equations. In fact, we first
need to generate two-input XOR/XNOR circuits, and then using a 2-to-1 multiplexer
produce the Sum and Cout outputs. Fig. 1 shows the block diagram of the proposed 1-
bit full adder cell, based on

Sum = (B⊕C)· A+(B⊕C)· A (3)

Cout = (B⊕C)·B+(B⊕C)· A. (4)

![image](https://github.com/Mushtaq0399/Term-Paper-Study/assets/139509924/dce34dfc-9d97-426f-8224-c84bcdb695e1)

Using multiplexers at the output nodes results in a low driving power for the design
shown in Fig. 1. To enhance the driving capability, first, we complement (3) and (4) to
obtain logic relations (5) and (6), respectively. Then, using NOT gates at the output
nodes, the desired signals are produced

Sum = (B⊕C)· A +(B⊕C)· A (5)

Cout = (B⊕C)· B +(B⊕C)· A . (6)

![image](https://github.com/Mushtaq0399/Term-Paper-Study/assets/139509924/e04d5e65-bdf5-4e52-aba0-0fe70fbef705)

The block diagram of the proposed full adder cell, which is based on relations (5) and
(6), is shown in figure 2. The presence of inverters at the output nodes decouples inputs
and outputs and provides a sufficient driving power. Therefore, this structure can be
efficiently used in any circuit configuration. considering Figs. 1 and 2, we separately present and
analyze corresponding circuits for XOR/XNOR and multiplexer modules to form the
novel full adder cell. In Section III-A, we present the transistor level implementation of
the novel XOR/XNOR functions. In Section III-B, the schematic of a 2-to-1 multiplexer
is presented. Finally, in Section III-C, the transistor level implementations of the
proposed full adder cells are presented.

![image](https://github.com/Mushtaq0399/Term-Paper-Study/assets/139509924/c95fc006-515c-4526-8067-255b37c1164d)

## Conclusion 

The proposed cells perform well with supply voltage scaling and even under different
output loads. When they are used in large adders, such as RCA, they outperform their
counterparts and make them to be fitting to the large circuits.
In addition, the susceptibility of full adders against both noise and process variations
was considered. In noise point of view, we observed that the proposed designs had a
close competition with other full adders, and in some cases, they outperformed them.
Finally, to study the robustness of the full adders against the diameter variations of
CNTs embedded in the channel of CNFET devices, we performed the MC transient
analysis. Simulation results confirmed that the proposed cells are more robust than other
cells with regard to process variation, making them suitable for implementing in the
CNFET technology

Files incuded: Final report for the observations and the original paper

Author for the report/study:

-[Mushtaq Hussain Shaik](https://www.linkedin.com/in/mushtaqhussainshaik/)

-Sundeep
