# 🛡️ NETWORKWALKS-B083--WEEK-3
## 🔐 Password Cracking &amp; Hash Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Networkwalks%20tools:-Hash%20Calculator;%20Password%20Cracker-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/password%20cracking-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Hash%20Analysis-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/John%20the%20Ripper%20JTR-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Jonny%20&%20GUI%JTR%20Network%20walks%20tools%20password%20cracker-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Idongesit%20Nkanga%Internship-C00000?style=flat-square" />
<p align="center">

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

p.s: I selected "John" for the path since my system did not show `john.exe`. Both are the saame.

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

#RESULT

<img width="598" height="240" alt="Screenshot 2026-09-24 014633" src="https://github.com/user-attachments/assets/4d739fde-820f-4541-99ff-5a57cb615cbd" />

#### 8️⃣ Verify the Result

Used the recovered password to open the original protected PDF and confirm that the password was correct.

---
<img width="893" height="430" alt="Screenshot 2026-09-24 015204" src="https://github.com/user-attachments/assets/8c565383-36de-4952-a113-2c3b6eae6694" />

I follwed same process to unlock the second and third pdf files

#SCREENSHOTS

<img width="806" height="444" alt="Screenshot 2026-09-24 015626" src="https://github.com/user-attachments/assets/e3b90b90-1287-4967-866a-e0e90c39c166" />


<img width="800" height="434" alt="Screenshot 2026-09-24 020048" src="https://github.com/user-attachments/assets/890a50e1-f079-45ce-9e7f-8518f668d8cf" />

#TASK 2

The second part of the practical used **NetworkWalks' browser-based security tools** to explore an alternative password-recovery workflow.

### 🧪 Methodology

1. 📄 Prepared the encrypted PDF files supplied for the practical.
2. 🌐 Uploaded the protected PDF to the **NetworkWalks Hash Calculator**.

   <img width="839" height="457" alt="Screenshot 2026-09-24 210558" src="https://github.com/user-attachments/assets/6ca3dddb-d7e7-4a40-9fda-4cfeb9ff7488" />

3. 🔎 Extracted the corresponding `$pdf$...` hash.
4. 📋 Copied the generated hash into the **NetworkWalks Password Cracker**.
5. ▶️ Started the password-recovery process.
6. ⏳ Waited for the tool to identify a matching password.

  #p.s The first attempt with the built-in word list showed a failed attempt
solution: i uploaded external wordlists and kept trying to get a match. "JTR_default_password.txt" wordlist had a match


https://github.com/user-attachments/assets/bff31fed-8b0b-4329-adaa-b345e08ef981


#Screenshot

<img width="917" height="457" alt="Screenshot 2026-09-24 220707" src="https://github.com/user-attachments/assets/2e87eb1a-99e2-4333-997c-244596c634c0" />

7. ✅ Tested the recovered password against the original protected PDF to verify the result.

   #Screenshot
   
   <img width="746" height="436" alt="Screenshot 2026-09-24 220820" src="https://github.com/user-attachments/assets/d6687b18-417a-4d8a-b1df-50fd65adacdc" />


🧠 Key Learning

This practical helped build a more complete understanding of the relationship between a password-protected PDF, its extracted hash, and password-auditing tools.

It also provided hands-on exposure to two different password-auditing approaches:

🖥️ A locally configured John the Ripper (JTR) + Johnny GUI environment
🌐 A browser-based NetworkWalks password-recovery workflow


💡 Main Takeaway

The exercise demonstrated how password complexity can affect the practicality of password recovery and reinforced the importance of using strong, unique passwords when protecting sensitive files.

📊 Practical Comparison
| 🔍 Feature          | 🖥️ Lab 1                    | 🌐 Lab 2                        |
| ------------------- | ---------------------------- | ------------------------------- |
| **Approach**        | Local password auditing      | Browser-based password recovery |
| **Primary Tool**    | John the Ripper + Johnny GUI | NetworkWalks Tools              |
| **Hash Extraction** | PDF Hash Extraction Tool     | NetworkWalks Hash Calculator    |
| **Hash Format**     | `$pdf$...`                   | `$pdf$...`                      |
| **Environment**     | Windows PC                   | Web Browser                     |
| **Verification**    | Original protected PDF       | Original protected PDF          |


Password-cracking tools can be used for legitimate security testing as well as unauthorized access.

This exercise was conducted exclusively against authorized laboratory files as part of cybersecurity training.


🏁 Conclusion

Week 3 provided valuable hands-on experience with password auditing and hash analysis.

Working with both John the Ripper (JTR) and NetworkWalks tools helped build a practical understanding of the complete password-auditing workflow — from extracting a PDF hash to submitting the hash for password recovery and verifying the result against the original protected document.

The practical also reinforced the importance of strong password practices, secure file protection, and responsible use of password-auditing tools within an authorized cybersecurity testing environment.


⭐ Cybersecurity Internship Portfolio

🔎 Hash Analysis
🔐 Password Security
🧪 Security Testing
💻 Practical Cybersecurity


---

## Author

**IDONGESIT NKANGA**  
Cybersecurity Intern — B083

LinkedIn: https://www.linkedin.com/in/idongesit-george-7b0125a8 

### Project Information

- **Program Name:** Cybersecurity program at Networkwalks
- **Week:** 02
- **Repository:** GitHub

