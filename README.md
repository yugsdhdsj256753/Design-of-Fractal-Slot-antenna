
# Improving the Sidelobe Level, Return Loss and Bandwidth of a Notch-Loaded TM30 Mode Patch Antenna

## 📡 Project Overview

This project focuses on the design and simulation of a **fractal-slot-loaded, notch-loaded microstrip patch antenna** based on the higher-order **TM30 mode**.

The proposed antenna uses a fractal slot at the center of the patch to manipulate the surface-current distribution and reduce unwanted out-of-phase currents. The project investigates important antenna parameters including **return loss, VSWR, gain, and radiation pattern**.

## 🎯 Objective

The primary objective was to design a fractal H-shaped notch-loaded patch antenna using an **Arlon CuClad 217 substrate** with a relative permittivity of **2.2** and substrate thickness of **1.5 mm**. The initial design objective targeted satellite communication applications at **3.09 GHz**.

## 💡 Working Principle

Higher-order TM30 mode patch antennas can contain unwanted **out-of-phase surface-current regions**, which can negatively affect sidelobe performance.

The proposed approach combines:

- Notch loading
- Fractal-slot loading
- Higher-order TM30 mode operation

The fractal slot is introduced near the unwanted current region to improve antenna characteristics such as sidelobe level, impedance matching, and bandwidth.

## 🛠️ Design Specifications

| Parameter | Value |
|---|---:|
| Patch Length (L) | 90 mm |
| Patch Width (W) | 101 mm |
| Slot Length (l) | 30 mm |
| Slot Width (w) | 30 mm |
| Ground Length (L1) | 140 mm |
| Ground Width (W1) | 150 mm |
| Feed Offset (dx) | 15 mm |
| Substrate | Arlon CuClad 217 |
| Relative Permittivity (εr) | 2.2 |
| Substrate Thickness | 1.5 mm |

## 🔧 Design Methodology

The antenna design process involved the following steps:

1. Creating the ground plane and substrate.
2. Designing the rectangular patch.
3. Creating the notch-loaded structure.
4. Developing the fractal slot through multiple iterations.
5. Combining the fractal slot with the patch.
6. Providing the feed.
7. Performing design validation.
8. Simulating and analyzing antenna performance.

## 📊 Simulation Results

| Parameter | Obtained Value |
|---|---:|
| Resonant Frequency | **2.02 GHz** |
| Return Loss | **−16.22 dB** |
| VSWR | **2.38** |
| Gain | **Approximately 8.9 dB** |

> **Note:** The initial design target was 3.09 GHz, while the final simulation result obtained resonance at 2.02 GHz.

## 📈 Performance Parameters Analyzed

The following antenna characteristics were analyzed:

- **Return Loss (S11)**
- **Voltage Standing Wave Ratio (VSWR)**
- **Antenna Gain**
- **Radiation Pattern**
- **Resonant Frequency**

## 📁 Project Structure

```text
├── README.md
├── Project_Report.pdf
├── Literature_Paper.pdf
├── Presentation.pptx
├── Antenna_Design/
│   ├── Ground_Plane
│   ├── Patch_Design
│   ├── Fractal_Slot
│   └── Feed_Design
└── Results/
    ├── Return_Loss
    ├── VSWR
    ├── Gain
    └── Radiation_Pattern
```

## 🔬 Reference Research

This project is based on the concept presented in:

**“Improving the Sidelobe Level, Return Loss and Bandwidth of Notch-Loaded TM30 Mode Patch via Fractal-Slot.”**

The research investigates the combination of notch loading and fractal-slot loading for improving the performance of higher-order mode patch antennas.

## 🚀 Future Improvements

- Optimize the antenna dimensions to achieve the intended **3.09 GHz** resonant frequency.
- Improve impedance matching and reduce VSWR.
- Optimize the feed position.
- Perform detailed parametric analysis of fractal-slot dimensions.
- Fabricate and experimentally validate the antenna.
- Compare simulated and measured results.

## 👨‍💻 Authors

**Yuvaraj Dhayal**  
Electronics and Communication Engineering

**Kantharaj S**

## 🧰 Tools and Technologies

- Antenna Simulation Software
- Electromagnetic Analysis
- Microstrip Patch Antenna Design
- RF Engineering

---

⭐ If you find this project interesting, consider giving the repository a star!
