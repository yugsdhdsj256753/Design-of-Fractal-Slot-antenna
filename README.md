
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

## 📊 Steps
### 📸 Antenna Design
<img width="526" height="572" alt="image" src="https://github.com/user-attachments/assets/c3690e15-911b-46c3-b065-379dba66cb0a" />
### creating a ground plane size of 140*150 mm^2
<img width="704" height="441" alt="image" src="https://github.com/user-attachments/assets/c91f5937-099b-4084-9f5f-301d35471e65" />
### creating the patch over the subtrate
<img width="751" height="445" alt="image" src="https://github.com/user-attachments/assets/c2c63afb-f2e4-483e-b7e4-e8ae2586f9db" />
### creation of fractal slot
### fractal slot after uniting
<img width="507" height="394" alt="image" src="https://github.com/user-attachments/assets/73887993-6090-4c0d-a070-1f2f1045047c" />
### iteration 1
<img width="451" height="385" alt="image" src="https://github.com/user-attachments/assets/f38bec98-b896-4f07-b347-0ad9bdfa4ccd" />
### 2nd iteration
<img width="469" height="413" alt="image" src="https://github.com/user-attachments/assets/5cfe977f-0e39-4fe8-83eb-da9340fb4ec2" />
### after further iterations
<img width="469" height="413" alt="image" src="https://github.com/user-attachments/assets/1770e49d-aeb2-4784-b6b4-4b03e9a1aab1" />
### patch with fractal slot
<img width="769" height="469" alt="image" src="https://github.com/user-attachments/assets/0a424e85-bd62-428c-8011-4b912b2843e7" />
### providing differntial feed
### front view
<img width="901" height="497" alt="image" src="https://github.com/user-attachments/assets/8fd1dd55-0f71-47db-854e-84894580bad5" />
### validation check
<img width="966" height="544" alt="image" src="https://github.com/user-attachments/assets/d8996222-e9da-4411-9041-39b800b2380f" />
## 📊 Simulation results
### Return Loss
<img width="980" height="572" alt="image" src="https://github.com/user-attachments/assets/158ed797-02c4-4fb7-8e3b-b5dc42435539" />
### VSWR
<img width="1013" height="610" alt="image" src="https://github.com/user-attachments/assets/b1a21a6d-de14-4997-995c-e96b0167df54" />


### Gain
<img width="1107" height="464" alt="image" src="https://github.com/user-attachments/assets/a0037258-4cd4-4794-a6e5-2d86f419b67b" />

### Radiation Pattern
<img width="780" height="640" alt="image" src="https://github.com/user-attachments/assets/2ec4da1f-1b1b-472a-aafe-66be2fb3e66b" />

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
