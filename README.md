# Hi, I'm Junchi Yan 👋

🎓 M.E. Graduate Student in Electrical Engineering | University of Virginia  
⚡ Power Electronics | Motor Drives | Electrical Hardware | Electrical System Integration

---

## About Me

I'm a graduate student in Electrical Engineering at the University of Virginia (2025–2026), with a B.Eng. in Electrical Engineering and Automation from Shenyang University of Technology.

My hands-on experience is in **electrical hardware**: motor controller PCB design, current sensing and protection circuits, board-level testing, and industrial electrical control cabinets with variable frequency drives (VFDs). I've spent 12 months in a motor controller R&D team and a summer in an electrical cabinet manufacturing and commissioning team, so I've seen hardware from schematic and layout through assembly, testing, and delivery.

At UVA, I've added analog IC design (TSMC 180nm) and control-oriented coursework to that foundation.

---

## Experience Highlights

### ⚙️ Motor Controller R&D Intern — Beijing, China
*Sep 2024 – Aug 2026 (12 months in two phases)*

- Contributed to a **12 kW motor controller**: drew the power board and driver board in Altium Designer, selected **80+ component footprints**, and routed layouts with EMI performance in mind.
- Assembled, soldered, and functionally tested **2 types of circuit boards**.
- Helped improve the **current-sensor signal conditioning circuit**: a single-supply op-amp stage amplifies the AC output-current signal and feeds an overcurrent threshold detector.
- Supported hardware-side bring-up of the control board: ran electrical-characteristic tests on **5 interface types** (GPIO, PWM, ADC, CAN, RS485) and improved the test fixture to speed up port testing.
- Built a Simulink model for a newly added module and used its generated C code as part of the verification workflow.

### 🏭 Electrical Control Systems Intern — Beijing, China
*May 2026 – Aug 2026*

- Followed the full manufacturing flow of industrial electrical control cabinets: design, production, commissioning, and quality control.
- Learned VFD speed-control schemes across **4 types of equipment** (pumps, fans, etc.); took part in component selection (**10+ components**), cabinet installation, and tuning of **20+ parameters**.
- On a lithium-battery powder classification system, did wiring verification for an ABB drive and low-voltage distribution components, and helped with PLC program debugging and continuity testing across **8 I/O points**.
- On a peanut-oil pressing line, completed cabinet assembly checks and factory commissioning, independently configured the basic parameters of multiple **ACS580 drives** (V/F mode, acceleration/deceleration time, overload protection), and helped commission **dozens of custom cabinets** for delivery.

---

## Projects

### 📡 High-Bandwidth Transimpedance Amplifier (TIA) — UVA, 2026
Designed a **5 kΩ transimpedance gain TIA** in **TSMC 180nm CMOS** targeting **250 MHz bandwidth** for optical receiver front ends.

- Quantified the Miller effect: computed equivalent input capacitance and dominant-pole frequency.
- Added a **cascode topology** and **inductive peaking**, and evaluated how much bandwidth each contributes.
- **Result:** reached the 250 MHz target at 5 kΩ gain; delivered a complete transistor-level design using the PDK.

### 🔌 Dual-Output Flyback Power Supply — Overseas Power Electronics Program, 2023
Led a team in designing a flyback supply: **220 V AC input → 5 V/2 A and 9 V/2.22 A outputs**.

- Closed-loop regulation using optocoupler isolation feedback and a TL431 reference; duty cycle adjusted to hold output voltage across load changes.
- Selected the core components and built and simulated the circuit in LTspice under multiple load conditions.
- **Result:** both outputs met specs in simulation; the instructor recommended me for one of only 2 recommendation letters in the class. The related paper was published at **AMCCE 2023**.

### 🔋 Cost Optimization of BLDC Motors for Power Tools — 2022–2023
*Undergraduate innovation project lead; extended into my thesis*

- Built a cost model covering copper, iron, and permanent magnet usage, and related **pole-arc coefficient to material cost** under efficiency constraints to find the best cost-performance parameters.
- Led the team: set **5 milestones**, assigned work (cost survey, electromagnetic calculation, simulation), and presented at the final defense.
- **Result:** ~15,000-word project report approved by the innovation competition; an ~8,000-word paper on pole-arc coefficient vs. motor cost, which later became the basis for my graduation project.

---

## Areas of Interest

- Motor drives and power converters
- Electrical hardware design: PCB, sensing, and protection circuits
- Electrical system design, integration, and commissioning
- Analog and power-oriented IC design

## Career Goals

I'm looking for engineering roles in **power electronics, motor drive hardware, and electrical system integration**, where I can keep doing hands-on work: designing, building, testing, and debugging real hardware. I'm also curious about how electrical hardware supports newer fields such as robotics, but power and drive hardware is where my experience is.

---

📫 **Contact:** yan597030@gmail.com
