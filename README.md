# 🛡️ NETWORKWALKS-B083--WEEK-3
## 🔐 Password Cracking &amp; Hash Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Skill-Linux%20tools-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Footprinting-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Whois%20nslookup%20whatweb%20curl -%20wafwoof%20dnsrecon-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Reconaissance%20&%20Footprinting%20with%20Maltego-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Idongesit%20Nkanga%Internship-C00000?style=flat-square" />
<p align="center">

**Cybersecurity Training & Internship Journey with NETWORKWALKS**

`🔎 Hash Analysis` • `🔐 Password Auditing` • `🧪 Security Testing` • `💻 Cybersecurity Lab`

</p>

---

## 📌 Overview

This week's practical focused on **Password Cracking & Hash Analysis**, exploring how password-protected PDF files can be assessed by extracting their hashes and testing them with different password-auditing tools.

The exercise provided hands-on experience with **hash extraction, password auditing, John the Ripper, and Johnny GUI** within a controlled cybersecurity laboratory environment.

### 🎯 Topics Covered

- 🔎 PDF hash extraction and identification of `$pdf$` signatures
- 🔐 Local password auditing with **John the Ripper (JTR)**
- 🖥️ Using **Johnny GUI** as a graphical frontend for JTR
- ⚙️ Configuring JTR with target files and attack options
- 🌐 Browser-based password recovery using NetworkWalks tools
- ✅ Verifying recovered passwords against the original PDF files

> ⚠️ **Disclaimer:** This experiment was performed strictly for educational and cybersecurity training purposes using authorized laboratory files in a controlled lab environment.

---

## 🧰 Tools & Technologies

| 🛠️ Tool / Technology | 🎯 Purpose |
|---|---|
| 🔐 **John the Ripper (JTR)** | Password auditing and recovery |
| 🖥️ **Johnny GUI** | Graphical frontend for John the Ripper |
| 📄 **PDF Hash Extractor** | Extraction of password hashes from protected PDF files |
| 🌐 **NetworkWalks Hash Calculator** | Browser-based PDF hash extraction |
| 🔓 **NetworkWalks Password Cracker** | Hash-based password recovery |
| 💻 **Windows PC** | Local cybersecurity laboratory environment |
| 🌐 **Web Browser** | Accessing browser-based security tools |

---

# 🧪 Lab 1 — Password Cracking with John the Ripper & Johnny GUI

The first practical involved configuring **John the Ripper** on Windows and using **Johnny GUI** to perform password recovery against an authorized password-protected PDF.

### 🔬 Methodology

#### 1️⃣ Install the Required Tools

Installed **John the Ripper** and **Johnny GUI** on the Windows system.

#### 2️⃣ Configure Johnny GUI

Configured Johnny to locate the `john.exe` executable inside the **John the Ripper `run` directory**.

#### 3️⃣ Extract the PDF Hash

Processed the encrypted PDF using a PDF hash extraction tool.

#### 4️⃣ Identify the Hash

Obtained the extracted PDF hash containing the `$pdf$` signature.

#### 5️⃣ Prepare the Hash File

Saved the extracted hash into a text file for use with John the Ripper.

#### 6️⃣ Load the Hash

Loaded the hash file into Johnny using the appropriate password-file option.

#### 7️⃣ Start Password Recovery

Initiated the password recovery process using John the Ripper through the Johnny GUI interface.

#### 8️⃣ Verify the Result

Used the recovered password to open the original protected PDF and confirm that the password was correct.

---

## 🔎 Redacted Hash Format

For security and documentation purposes, the actual hash value has been redacted.

```text
$pdf$4*4*128*[REDACTED]
