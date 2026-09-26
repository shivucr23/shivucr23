<p align="center">
  <img src="assets/banner.jpg" alt="Automotive Embedded Systems Banner" width="100%" style="border-radius: 8px;" />
</p>

<p align="center">
  <a href="https://github.com/shivucr23">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=false&width=750&height=50&lines=Automotive+Embedded+Software+Engineer;ECU+Bootloaders+%7C+UDS+ISO+14229;In-Vehicle+Networking+%7C+CAN+%26+CAN-FD;Automotive+Cybersecurity+%7C+SecOC+%26+SHE;Binary+Workstations+%7C+Vector+HexView" alt="Typing Headline" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Windows_x64-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows" />
</p>

---

### 👨‍💻 Engineering Profile

Automotive systems and firmware engineer specializing in **ECU Bootloader Architecture**, **Diagnostic Protocols (ISO 14229 / ISO 15765-2)**, and **Embedded Firmware Security**. Experienced in designing deterministic reflashing workflows, in-vehicle network stacks (CAN, CAN-FD), and hardware-grade cryptographic workstations.

- 🚗 **ECU Bootloader Engineering**: Complete flashing pipelines over CAN and CAN-FD networks with diagnostic session control, block-by-block pipelined transfers, and flash driver integration.
- 🛡️ **Automotive Firmware Security**: Implementing and modeling specifications for AUTOSAR SecOC, HIS SHE v1.1, secure boot validation, digital signature verification, and automotive PKI.
- 🔬 **Binary & Firmware Processing**: Comprehensive parsing, remapping, slicing, and checksumming of Motorola S-Records (.s19), Intel HEX (.hex), Volvo VBF (.vbf), and binary images matching Vector HexView algorithms.
- ⚡ **Standalone Tooling**: Author of production-grade, zero-dependency Windows desktop tools for calibration, reflashing, and cryptographic analysis.

---

### 🛠️ Technical Competencies

| Domain | Specialization & Standards |
| :--- | :--- |
| **Diagnostic Protocols** | ISO 14229-1 (UDS), ISO 15765-2 (DoCAN), ISO 11898 (CAN / CAN-FD), AUTOSAR Diagnostic Stack |
| **Core Languages** | C, C++, Python 3, JavaScript (React / Vite), Shell Scripting |
| **Firmware & Data Formats** | Motorola S-Record (.s19, .s28, .s37), Intel HEX (.hex, .ihx), Volvo VBF (.vbf v2.1), Raw Binary (.bin) |
| **Hardware Cryptography** | AES-128/256 (CBC, GCM), RSA-PSS, ECDSA NIST P-256, Ed25519, HMAC, AES-CMAC, Vector Checksums (Methods 0–20) |
| **CAN Hardware Interfaces** | PEAK PCAN-USB, Vector Informatik (XL Driver Library), Kvaser, Intrepid ValueCAN, Virtual CAN |
| **Workstation Architecture** | FastAPI, React Desktop Workstations, PyInstaller Single-File Executables, CI/CD Automation |

---

### 🚀 Featured Engineering Repositories

#### 🚗 [Automotive-ECU-Tools — Standalone Engineering Workstation Suite](https://github.com/shivucr23/Automotive-ECU-Tools)
A production-grade suite of zero-dependency desktop applications for automotive firmware engineers:

<table align="center" width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4 align="center">🚀 Automotive UDS Download Tool (v1.3.1)</h4>
      <ul>
        <li><b>Protocol Stack</b>: Complete ISO 14229 Diagnostic Session Control, Security Access (0x27), Routine Control, and block flashing.</li>
        <li><b>Transport Layer</b>: ISO 15765-2 DoCAN handling Single Frames, First Frames, Consecutive Frames, and Flow Control.</li>
        <li><b>Hardware Support</b>: PEAK PCAN, Vector CAN, Kvaser, and Virtual CAN.</li>
        <li><b>Binary</b>: Single-file zero-dependency executable (<code>UDS_Download_Tool.exe</code>).</li>
      </ul>
      <p align="center">
        <a href="https://github.com/shivucr23/Automotive-ECU-Tools/releases/download/v1.0.0/UDS_Download_Tool.exe">
          <img src="https://img.shields.io/badge/Download-UDS__Download__Tool.exe-0078D6?style=for-the-badge&logo=windows" alt="Download UDS Tool" />
        </a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">🛡️ CipherHex Workstation (v1.0.0)</h4>
      <ul>
        <li><b>Vector HexView Alternative</b>: High-performance memory remapping, segment inspection, and binary diffing.</li>
        <li><b>Vector Checksums</b>: Exact match for Vector Table 3-3 algorithms (Methods 0–20, CRC32, GM ByteSums, SHA-256).</li>
        <li><b>Crypto Suite</b>: AES-128/256, ECDSA P-256 signatures, AUTOSAR SecOC, and HIS SHE modeling.</li>
        <li><b>Binary</b>: Single-file zero-dependency executable (<code>CipherHex.exe</code>).</li>
      </ul>
      <p align="center">
        <a href="https://github.com/shivucr23/Automotive-ECU-Tools/releases/download/v1.0.0/CipherHex.exe">
          <img src="https://img.shields.io/badge/Download-CipherHex.exe-2ea44f?style=for-the-badge&logo=windows" alt="Download CipherHex" />
        </a>
      </p>
    </td>
  </tr>
</table>

---

### 📊 GitHub Activity & Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shivucr23&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=79c0ff&text_color=c9d1d9" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shivucr23&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" alt="Top Languages" />
</p>

---

<p align="center">
  <i>"Deterministic engineering for mission-critical automotive embedded software."</i>
</p>
