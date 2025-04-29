# CERN Summer Student Programme Project  

## Project Title  
**Analysis and Data Processing for the MTD BTL Detector at HL-LHC**  

## Supervisors  
- Mehmet Ozgur Sahin  
- Flavia Cetorelli  

---

## Project Overview  
This project focuses on the **MIP Timing Detector (MTD)** for the **High-Luminosity Large Hadron Collider (HL-LHC)**. The MTD introduces precise timing measurements to improve vertex reconstruction, critical for disentangling pile-up interactions in high-luminosity conditions. Key tasks include:  
- Data processing and signal analysis.  
- Studying **Minimum Ionizing Particles (MIPs)** and their interactions with the detector.  

---

## Key Components  
### 1. **MTD BTL Detector**  
- **LYSO scintillator crystals** + **SiPMs** + **TOFHIR readout chips**.  
- Structured in azimuthal segments (10° each) with 6 readout units per segment.  

### 2. **TOFHIR Chip**  
- Radiation-tolerant ASIC for signal amplification, shaping, and digitization.  
- Features:  
  - **TDC (Time-to-Digital Converter)**: Measures signal timing.  
  - **QDC (Charge-to-Digital Converter)**: Measures integrated charge.  
  - **CFD (Constant Fraction Discriminator)**: Enhances timing precision.  

### 3. **Data Analysis Pipeline**  
- Raw data conversion and event coupling.  
- Filtering L1-triggered events for relevant physics.  

---

## Tools & Technologies  
- **Programming**: Python  
- **Libraries**:  
  - `numpy`
  - `matplotlib
  - `ROOT`
- **Platform**: **Jupyter SWAN** (CERN’s cloud-based analysis environment).  
