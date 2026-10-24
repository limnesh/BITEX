<div align="center">

# 🔐 Quantum Security 101

### From Breaking RSA to Quantum Key Distribution with AI

**One fictional bank. Three interactive notebooks. A journey from classical encryption to quantum-safe communication.**

[![Event](https://img.shields.io/badge/MeetICT%20%26%20BITEX-2026-1671c5?style=for-the-badge)](https://github.com/limnesh/BITEX)
![Location](https://img.shields.io/badge/Location-Bahrain-087f8c?style=for-the-badge)
![Format](https://img.shields.io/badge/Format-Interactive%20Google%20Colab-f59e0b?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Curious%20Beginners%20Welcome-16a34a?style=for-the-badge)

**28 October 2026 · 12:00–1:00 PM (Bahrain time) · Gulf Convention Centre, Gulf Hotel, Bahrain**

**Workshop conducted by Limnesh Augustine**  
Project Manager · Gulf Business Machines (GBM), Bahrain

</div>

---

## 🚀 Open the three notebooks

Work through them **in order**. Each notebook contains explanations, runnable Python cells and interactive controls.

| | Workshop notebook | Launch in Google Colab | What you will do |
|---|---|---|---|
| **01 🏦** | **BSB Banking, IPsec & Harvest Now–Decrypt Later**<br/>[`01_ClassicalSecurity.ipynb`](https://github.com/limnesh/BITEX/blob/main/01_ClassicalSecurity.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/limnesh/BITEX/blob/main/01_ClassicalSecurity.ipynb) | Observe key exchange, encrypt a banking record, and see what Eve can record. |
| **02 ⚛️** | **From Classical Bits to Qubits and Shor's Algorithm**<br/>[`02_QuantumComputing.ipynb`](https://github.com/limnesh/BITEX/blob/main/02_QuantumComputing.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/limnesh/BITEX/blob/main/02_QuantumComputing.ipynb) | Experiment with Bloch spheres, gates, measurements, and the quantum threat to public-key cryptography. |
| **03 🔦** | **Quantum Key Distribution, Satellites & Machine Learning**<br/>[`03_QKDandML.ipynb`](https://github.com/limnesh/BITEX/blob/main/03_QKDandML.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/limnesh/BITEX/blob/main/03_QKDandML.ipynb) | Send simulated photon pulses; explore BB84, Eve, QBER, reconciliation, privacy amplification, SKR and AI. |

**📂 [Browse all workshop files on GitHub](https://github.com/limnesh/BITEX)**

---

## 👨‍🚀 About the presenter — Limnesh Augustine

**Limnesh Augustine** is an **Electronics and Communication Engineer (University of Calicut, 2003)** and **Project Manager at Gulf Business Machines (GBM), Bahrain**, with over two decades of IT experience. He previously served as **Head of IT for the Works Directorate and subsequently the Planning & Future Systems Directorate at the Ministry of Interior, Bahrain, until 2019**.

Beyond technology, he is an internationally recognized **3D anamorphic artist**, a **multiple Guinness World Record holder** (Bahrain and USA), recipient of Italy’s **Madonnari title**, and an **EASA-licensed Private Pilot**. His creative work includes collaborations with **FAO, UNDP, WHO and WWF** and participation in UN-related initiatives. Explore his art at **[3DCouple.com](https://3dcouple.com/)** and his aviation learning project at **[ATCSpeak](https://www.atcspeak.com/about)**.

His interests span **quantum communication, QKD, free-space optics and AI**. He has completed postgraduate studies at **IIT Delhi**, presented a **2025 IEEE paper** on AI-based art evaluation, and won the **2019 CID hacking competition** organized by Bahrain’s Ministry of Interior.

> **Why this workshop?** To make quantum security approachable through interactive experiments connecting classical encryption, quantum computing and photon-based key distribution.

*This is an independent educational workshop. BSB is fictional; the notebooks demonstrate simplified research and teaching models rather than production banking or operational quantum systems.*

## 📚 Continue exploring

| Project / website | Explore |
|---|---|
| **DPS-QKD over Free-Space Optical Channels — Project Report** | [📖 Read the research report](https://limnesh.github.io/QuantumKeyDistribution-DPS/DPS_QKD_FSO_Project_Report_v1.0.html) |
| **QKD over Free-Space Optical Communication — Project Report** | [📖 Read the research report](https://limnesh.github.io/QuantumKeyDistribution-FSO/QKD_FSO_Project_Report-v1.0.html) |
| **3D Couple — Art that changes perspective** | [🎨 Visit 3dcouple.com](https://3dcouple.com/) |
| **ATCSpeak — Aviation communication practice** | [✈️ Visit ATCSpeak](https://www.atcspeak.com) |
| **Workshop source files and updates** | [🔐 GitHub · limnesh/BITEX](https://github.com/limnesh/BITEX) |

---

<details>
<summary><strong>🛠️ Troubleshooting and important notes</strong></summary>

- **The notebook opens but a button does nothing:** Run its setup and relevant widget-creation cell. In Google Colab, interactive widgets require the notebook runtime to be connected.
- **`ModuleNotFoundError` (Qiskit, scikit-learn, etc.):** Run the Setup cell. A fresh Colab environment does not always have all dependencies installed.
- **`NameError` or missing variables:** A previous cell has not run. Restart the session and follow the notebook order.
- **Charts or measurements change each time:** Some demonstrations intentionally use randomness. Quantum simulations are often sampled, and ML models may involve stochastic training.
- **A toy 9-bit DH example is broken quickly:** That is intentional. It illustrates the mathematics; it is not the security level of a modern 2048-bit finite-field DH group.
- **A displayed quantum circuit includes modular-operation placeholders:** The architecture diagram should not be mistaken for a fully implemented, runnable fault-tolerant Shor circuit.
- **A secret key rate is displayed:** Treat it as a model output under stated assumptions, not a deployment guarantee or a composable finite-key security proof.

</details>

<div align="center">

### Keep experimenting. Ask why. Change one variable. Observe the result.

**From 0 and 1 to photons, phase, and the future of secure communication.**

⭐ If these materials helped you, consider starring the [BITEX repository](https://github.com/limnesh/BITEX).

</div>
