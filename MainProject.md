# A Single Inductor Multi-Port Power Converter for Electric Vehicle Applications
**Abstract :**
This project presents a non-isolated multi-port DC-DC converter designed for electric vehicle (EV) applications. It integrates two input sources — solar PV and battery — using a single inductor, reducing component count and overall system complexity. The converter provides dual regulated outputs suitable for traction motors and auxiliary EV loads, ensuring efficient energy management and flexible power distribution.

**Overview :**
The converter operates in two primary modes — battery charging and battery discharging. In discharging mode, both PV and battery supply power to the load, while in charging mode, the PV source alone delivers energy to both the battery and load. This topology enables smooth energy transfer, reduced losses, and improved voltage control. The design emphasizes simplicity, compactness, and high efficiency, making it ideal for EV powertrain integration.


**Simulation diagram :**
![projectimage](https://github.com/user-attachments/assets/6ca6ce51-c812-4657-8db5-985fa88f4aa0)

**Tools & Results :**
The system is modeled and simulated in MATLAB/Simulink, validating stable operation, balanced current flow, and voltage regulation across varying load conditions. The results demonstrate effective hybrid energy utilization, confirming the converter’s suitability for renewable-integrated EV systems.

**Operation modes :**
![operation_modes](https://github.com/user-attachments/assets/99b0d893-c831-4f93-ac3c-798a7b1f842e)


**Key Takeaways :**
* Combines solar and battery sources through a single-inductor design for higher efficiency and compact architecture.
* Enables bidirectional power flow, supporting both charging and discharging modes in EV systems.
* Achieves flexible voltage control and reduced component count, lowering cost and improving reliability.
