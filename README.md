<h1 align="center">🔊 Multistage Amplifier Design</h1>

<p align="center">
BJT • MOSFET • Analog Design • LTSpice
</p>

---

## 🔍 Project Overview

This project presents the **design, simulation, and hardware implementation** of a multistage analog amplifier.

Developed for **ELE214 Electronics Laboratory – I**, the amplifier consists of:

✔️ Buffer Stage (BJT)  
✔️ Equalizer Stage (Band-Pass Filter)  
✔️ Gain Stage (MOSFET)  

The project covers the complete workflow from analytical calculations to lab validation.

📄 A detailed report is included in this repository.

---

## 🎯 Design Goals

- Stable multistage amplification  
- Controlled frequency band  
- Gain stage with Av ≈ 8  
- Clean signal transfer between stages  

---

## ⚙️ Circuit Architecture

### 1️⃣ Buffer Stage
- Implemented using **2N2222 BJT**
- Gain ≈ 1
- Provides high input impedance and low output impedance

---

### 2️⃣ Equalizer Stage
- Passive **band-pass filter**
- Frequency range:
  - Low cutoff: **780 Hz**
  - High cutoff: **12.2 kHz**
- Shapes the frequency response

---

### 3️⃣ Gain Stage
- Implemented using **IRF510 MOSFET**
- Designed gain: **Av = 8**
- Provides main signal amplification

---

## 📊 Key Results

| Parameter | Result |
|--------|--------|
| Final Stage Gain | 8 |
| Input Signal | ~60 mV |
| Output Signal | ~480–500 mV |
| Bandwidth | 780 Hz – 12.2 kHz |
| Buffer Gain | ≈1 |

---

## 🧪 Simulation

Simulated in **LTSpice**:

- Buffer stage verification  
- Bandpass frequency response  
- Gain stage validation  
- Full multistage response  

Simulation confirmed analytical calculations.

---

## 🛠️ Hardware Implementation

The circuit was built and tested on a **breadboard** using:

- Signal generator  
- Oscilloscope measurements  

Lab results closely matched simulations.

---

## 📷 Circuit & Measurements

<p align="center">
<img width="916" height="292" alt="image" src="https://github.com/user-attachments/assets/48bd4a60-36d2-4df9-9b5e-2848e65404cb" />
<img width="830" height="459" alt="image" src="https://github.com/user-attachments/assets/a4c4b620-01d8-45a1-be9e-2936fb05125a" />

V(n004) (red line) indicates the input signal 100mV, V(n007) (blue line) is 
the output of the buffer stage and it is almost 100 mV, V(n009) (green line) is the output of the 
equalizer stage and it is 60 mV,  and the last one V(vout) (pink line) is the output of the gain 
stage and approximately 480 – 500 mV. 

</p>

---


---

## 📚 References

Sedra/Smith, Boylestad, Razavi, and other analog design sources.  
See full report for citations.

---

## 👩‍💻 Author

**Betül Atalay**  
Electrical & Electronics Engineering  
Hacettepe University

---

⭐ If you find this project interesting, consider starring the repo!

