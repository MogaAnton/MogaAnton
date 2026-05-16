# Hi there! I'm Moga Anton Ioan 👋

### 🚀 Automation Student and Aspiring Engineer
I sit at the intersection of raw physics, mathematical modeling, and low-level firmware. I specialize in translating complex control algorithms and dynamic system architectures into efficient, robust, and safe embedded C/C++ code.

* 📍 **Location:** Cluj-Napoca, Romania
* 🎓 **Education:** Automation & Applied Informatics — Technical University of Cluj-Napoca (UTCN)
* 💼 **Looking for:** Experience, Interships and the chance to prove myself

---

## 🛠️ Technical Skillset

| Category | Technologies & Frameworks |
| :--- | :--- |
| **Programming Languages** | Embedded C, C++, MATLAB script, Java |
| **Hardware & MCUs** | ATmega32, ATmega328P, Arduino Architecture, Basic Electronics |
| **Simulation & Modeling** | MATLAB, Simulink, Simscape Electrical, Proteus 8 Design Suite |
| **Tools & Version Control** | MATLAB, Microchip Studio, Git, GitHub, Visual Studio, Intelij IDEA |

---

## 📂 Featured Engineering Projects

### 🌡️ [Automated Thermostat & Fan Controller](https://github.com/MogaAnton/Embedded-Project)
An automated, temperature-regulated cooling fan system modeled entirely within a localized simulation layout.
* **Core Focus:** Interfaced an ATmega32 microcontroller with an LM35 thermal resistor via the on-chip ADC to adjust a DC cooling fan motor dynamically based on ambient conditions.
* **The Highlight:** Engineered a **4°C software hysteresis buffer zone** to prevent rapid motor chattering/hardware oscillation at the exact setpoint frontier. Integrated simulated current-amplification switching topologies to overcome standard microcontroller GPIO limitations.
* **Tech Stack:** Embedded C, Microchip Studio, Proteus 8 Design Suite, ATmega32.

### 📟 [High-Efficiency DC-DC Buck Converter: MBD Lifecycle](https://github.com/MogaAnton/Power-Electronics-Project)
A complete Model-Based Design (MBD) workflow showcasing the full engineering lifecycle of a power electronic synchronous buck converter.
* **Core Focus:** Designed analytical components from scratch, implemented first-principles switched-state ODE models in Simulink, designed a closed-loop controller using the Guillemin-Truxal technique, and verified hardware robustness using high-fidelity Simscape physical modeling with parasitics/tolerances.
* **The Highlight:** Discretized the controller mapping (`c2d`) into a recursive difference equation implemented natively in production Embedded C within a timer-driven ISR for an ATmega328P, completing a **Software-in-the-Loop (SiL)** pipeline.
* **Tech Stack:** MATLAB, Simulink, Simscape Electrical, Embedded C.

### 📈 [Advanced System Identification & Mathematical Modeling](https://github.com/MogaAnton/System-Identification-Project)
A comprehensive repository containing high-performance regression tools engineered to map out both static and high-order dynamic black-box systems.
* **Core Focus:** Bypassed high-level black-box toolboxes to implement multi-variable least-squares solvers from scratch. Built optimized vectorized grid architectures (`meshgrid` variations) to completely eliminate iterative processing loop penalties.
* **The Highlight:** Designed an **Exponent-Table Polynomial Expansion routine** for high-order **Nonlinear ARX (NARX)** models, evaluating them via both One-Step-Ahead Prediction and autonomous Free-Running Simulation modes to strictly track model generalization and catch overfitting boundaries.
* **Tech Stack:** MATLAB.

### 🦯 [Smart Cane for the Visually Impaired](https://github.com/MogaAnton/Arduino-Project)
An assistive hardware proximity-sensing cane built to provide real-time proactive navigation feedback.
* **Core Focus:** Utilized an HC-SR04 ultrasonic sensor array to measure physical object time-of-flight distances, orchestrating a dual tactile (vibration motor) and auditory (piezo buzzer) notification profile.
* **The Highlight:** Implemented low-side saturated switching using a 2N2222 NPN transistor to handle high inductive current draw, paired with a 1N4148 flyback diode snubber network to absorb back-EMF spikes and isolate the MCU.
* **Tech Stack:** Arduino (C++), Hardware Prototyping, PCB Layout.

---

## 🔄 What I am up to nowadays

* **🎓 Academic Focus at UTCN:** I am currently advancing through my curriculum at the Technical University of Cluj-Napoca. My recent academic deep dives are centered around learning **PLC Architecture and Applications** working in TIAPortal, **Hydro-Pneumatic Control Equipment** architecture, and **Real-Time-Systems**.
* **💻 Project Developments:**
    * Getting the finishing touches on my Industrial Informatics Project - A completely functional Car rental Web Application.
    * Want to start a project using PLC's - An automated assembly line designed in TIAPortal.
    * A 3D Modelling project using Fusion 360 is on its way.
      
* **📚 Current Technical Focus & Learning Goals:**
    * Deepening my mastery of discrete-time system transformations (`c2d`) and numerical vectorization styles to run multi-variable control loops efficiently on low-power, constrained microcontrollers.
    * Starting to work on my Licence Paper - in the field of Control Engineering and Bio-Medical Equipment.

---

## 🎯 Goals & Aspirations

* 🏎️ **Industrial & Automotive Integration:** My primary goal is to deploy complex control algorithms (like Field-Oriented Control for electric vehicles or state-space robotics arrays) onto rugged production microcontrollers.
* ⚡ **Advanced MBD Mastery:** I am actively focused on deepening my expertise in Model-Based Design paradigms, Hardware-in-the-Loop (HiL) simulation architectures, and safety-critical embedded standards.
* 🌐 **Bridging Realities:** I aspire to build smart hardware systems that operate flawlessly in unpredictable physical environments, making low-level engineering more accessible, safe, and impactful.

---

## 📫 Let's Connect!
* **LinkedIn:** [https://www.linkedin.com/in/anton-ioan-moga/]
* **Email:** [mogaantonioan@gmail.com]

<!--
**MogaAnton/MogaAnton** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
