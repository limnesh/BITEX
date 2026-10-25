<div align="center">

# 🔐 Quantum Security 101

### From Breaking RSA to Quantum Key Distribution with AI

**One fictional bank. Three interactive notebooks. A journey from classical encryption to quantum-safe communication.**

[MeetICT & BITEX 2026](https://github.com/limnesh/bitex) · Bahrain · Interactive Google Colab · Beginners welcome

**28 October 2026 · 12:00–1:00 PM (Bahrain time) · Gulf Convention Centre, Gulf Hotel, Bahrain**

**Workshop conducted by Limnesh Augustine**  
Project Manager · Gulf Business Machines (GBM), Bahrain

**🏠 [Visit the Workshop Website](https://limnesh.github.io/bitex/)**

</div>

---

## 🚀 Jupyter Notebook Links

Work through them **in order**. Each notebook contains explanations, runnable Python cells and interactive controls.

| | Workshop notebook | Launch in Google Colab | What you will do |
|---|---|---|---|
| **01 🏦** | **BSB Banking, IPsec & Harvest Now–Decrypt Later** | [Open in Colab ↗](https://colab.research.google.com/github/limnesh/bitex/blob/main/01_ClassicalSecurity.ipynb) | Observe key exchange, encrypt a banking record, and see what Eve can record. |
| **02 ⚛️** | **From Classical Bits to Qubits and Shor's Algorithm** | [Open in Colab ↗](https://colab.research.google.com/github/limnesh/bitex/blob/main/02_QuantumComputing.ipynb) | Experiment with Bloch spheres, gates, measurements, and the quantum threat to public-key cryptography. |
| **03 🔦** | **Quantum Key Distribution, Satellites & Machine Learning** | [Open in Colab ↗](https://colab.research.google.com/github/limnesh/bitex/blob/main/03_QKDandML.ipynb) | Send simulated photon pulses; explore BB84, Eve, QBER, reconciliation, privacy amplification, SKR and AI. |

**📂 [Browse all workshop files on GitHub](https://github.com/limnesh/bitex)**

---

## 👨‍🚀 About the presenter — Limnesh Augustine

**Limnesh Augustine** is an **Electronics and Communication Engineer (BTech)** and **Project Manager at Gulf Business Machines (GBM), Bahrain**, with over two decades of IT experience. He previously served as **Head of IT** for the Works Directorate and subsequently the Planning & Future Systems Directorate at the **Ministry of Interior, Bahrain**, until 2019.

Beyond technology, he is an internationally recognized **3D anamorphic artist**, a multiple **Guinness World Record holder** (Bahrain and USA), recipient of Italy’s **Madonnari title**, and an **EASA-licensed Private Pilot(Airplane)**. His creative work includes collaborations with **FAO, UNDP, WHO and WWF** and participation in UN-related initiatives. Explore his art at **[3DCouple.com](https://3dcouple.com/)** and his aviation learning project at **[ATCSpeak](https://www.atcspeak.com)**.

His interests span **Quantum computing, Quantum communication, QKD, free-space optics and AI**. He has completed postgraduate studies in Quantum Communications at **IIT Delhi**, presented a **2025 IEEE paper** on AI-based art evaluation, and won the **2019 Hacking (CTF) competition** organized by CID, Ministry of Interior, Bahrain.

> **Why this workshop?** To make quantum security approachable through interactive experiments connecting classical encryption, quantum computing and photon-based key distribution.

*This is an independent educational workshop. BSB is fictional; the notebooks demonstrate simplified research and teaching models rather than production banking or operational quantum systems.*

## 📚 Continue exploring

| Project / website | Explore |
|---|---|
| **DPS-QKD over Free-Space Optical Channels — Project Report** | [📖 Read the research report](https://limnesh.github.io/QuantumKeyDistribution-DPS/DPS_QKD_FSO_Project_Report_v1.0.html) |
| **QKD over Free-Space Optical Communication — Project Report** | [📖 Read the research report](https://limnesh.github.io/QuantumKeyDistribution-FSO/QKD_FSO_Project_Report-v1.0.html) |
| **3D Couple — Art that changes perspective** | [🎨 Visit 3dcouple.com](https://3dcouple.com/) |
| **ATCSpeak — Aviation communication practice** | [✈️ Visit ATCSpeak](https://www.atcspeak.com) |
| **Workshop source files and updates** | [🔐 GitHub · limnesh/bitex](https://github.com/limnesh/bitex) |

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

⭐ Please take a moment to **[complete our workshop feedback survey](https://forms.gle/X3uCjLjDbuF2Btem7)**. Your feedback is greatly appreciated!

</div>
