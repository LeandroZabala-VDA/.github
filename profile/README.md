# VDA Project — Open Hardware for Arterial Diameter Variation Measurement

Welcome to the GitHub organization dedicated to the **open-source development of a biomedical acquisition system** for non-invasive measurement of **Arterial Diameter Variation (VDA)**.

![9ccd222b-6bfd-4f00-9343-ff1c3de103f2~1](https://github.com/user-attachments/assets/00095fd3-da60-4000-aef0-590769a40078)

## 👤 About the Author

This project was developed by **Leandro Zabala**, Electronics Engineer from the **National University of Mar del Plata (UNMDP)**, as part of the final undergraduate thesis carried out in collaboration with the **Bioengineering Laboratory (LABI)**. The system is the result of an interdisciplinary effort that combines electronics, signal processing, software development, and biomedical engineering.

## 🧭 Project Overview

The goal of this project was to design, build, and characterize a **non-invasive, high-resolution acquisition system** capable of capturing VDA signals with high signal-to-noise ratio and clinical-grade safety standards.

The system consists of:
- A **custom piezoelectric sensor** in wristband format, placed over the radial artery.
- A **signal acquisition unit**, with analog conditioning, 16-bit ADC, galvanic isolation, and USB connectivity.
- A **Python-based GUI** for configuration, real-time visualization, and data logging.

All components were developed from scratch and are made freely available under open-source licenses.

## 📚 Repository Structure

This GitHub organization contains the following repositories:

- [`VDA_Hardware`](https://github.com/LeandroZabala-VDA/VDA_Hardware):  
  Contains all PCB designs, schematics, and BOMs created in Eagle.  
  Includes the acquisition board and front panel PCBs.

- [`VDA_Firmware`](https://github.com/LeandroZabala-VDA/VDA_Firmware):  
  C firmware for STM32 microcontroller. Handles data acquisition, AGC logic, USB CDC communication, and real-time control.

- [`VDA_GUI`](https://github.com/LeandroZabala-VDA/VDA_Software):  
  Python-based graphical interface using PyQt5. Allows live monitoring, configuration, and logging of acquired signals.

- [`VDA_Mechanics`](https://github.com/LeandroZabala-VDA/VDA_Mechanical):  
  STL files and source CAD models for 3D-printed components: wrist sensor housing and acquisition unit enclosure.

Each repository is documented with its own README and includes images, version information, and setup instructions.

## 🔬 Scientific & Research Impact

The system was validated in both laboratory conditions and real-world tests. Over **200 patients** were studied using an earlier version of the system, and the data collected contributed to a **peer-reviewed publication in IEEE**. The signals captured with this device are suitable for the extraction of cardiovascular health markers, such as:

- Arterial stiffness and aging indicators
- Pulse wave reflection and augmentation index
- Cardiovascular risk screening

The open nature of the project aims to promote further research, student involvement, and collaborative development.

## 🛠️ Get Involved

Whether you're a biomedical researcher, engineer, or student, you're welcome to explore, fork, and contribute!

---

> *This project was completed as a graduation thesis at the Faculty of Engineering, UNMDP, under the guidance of researchers from the Bioengineering Laboratory (LABI).*
