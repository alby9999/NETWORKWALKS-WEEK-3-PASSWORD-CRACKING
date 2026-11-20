# PDF Password Cracking & Hash Extraction

**Cybersecurity Internship | Networkwalks | Week 03**

## 1. Project Overview

As part of Week 03 of my Networkwalks Cybersecurity Internship, I worked on two practical tasks based on PDF password cracking and hash extraction.

The aim of these activities was to understand how password-protected PDF files work and how different tools can be used to recover their passwords. I worked with John the Ripper and its graphical interface, Johnny, in the first module. In the second module, I used Networkwalks' online tools to generate a PDF hash and retrieve the corresponding password.

Both tasks were completed on my **Windows PC**, by following the instructions provided in the internship PDFs.

### What I worked on

- Setting up John the Ripper and Johnny GUI on Windows.
- Extracting password hashes from protected PDF files.
- Performing dictionary-based password attacks.
- Using Networkwalks online tools for hash generation and password recovery.
- Verifying the recovered passwords by opening the original PDF files.

---

## 2. Lab Environment

| **Parameter** | **Details** |
|---|---|
| Internship | Networkwalks |
| Week | Week 03 |
| Operating System | Windows |
| Domain | Cybersecurity & Ethical Hacking |
| Module 1 Tool | John the Ripper (JTR) |
| Graphical Interface | Johnny GUI |
| Module 1 Hash Extractor | Online Hash Crack |
| Module 2 Tools | Networkwalks Hash Calculator & Password Cracker |
| File Format | PDF |

### Tools Used

**John the Ripper (JTR)**

An open-source password auditing tool used to test password strength by checking possible password candidates against extracted hashes.

**Johnny GUI**

A graphical interface for John the Ripper. It makes it easier to configure the tool, load hash files, and start password attacks.

**Online Hash Crack**

A web-based utility used to extract password hashes from encrypted PDF documents.

**Networkwalks Hash Calculator**

An online tool used to generate or extract the password-related hash from a protected PDF file.

**Networkwalks Password Cracker**

A browser-based tool used to test password candidates against the extracted PDF hash and retrieve a matching password.

---

## 3. Module 1 – Password Cracking with John the Ripper

### Overview

The first task focused on recovering the password of the assigned protected PDF using John the Ripper and Johnny GUI.

I started by downloading and setting up the required software on Windows. After configuring Johnny with the John the Ripper executable, I extracted the PDF hash, saved it in a text file, and loaded it into Johnny to perform the password attack.

### Steps Performed

**Step 1: Setting up John the Ripper and Johnny**

- Downloaded John the Ripper for Windows from the official website.
- Extracted the downloaded files.
- Downloaded and installed Johnny GUI.
- Opened Johnny and accessed its settings.
- Located and selected the `john.exe` file from the extracted `run` folder.

This connected Johnny with the John the Ripper engine and prepared the tool for the practical task.

**Step 2: Extracting the PDF Hash**

- Downloaded the assigned password-protected PDF file, `My Locked PDF1.pdf`.
- Opened the Online Hash Crack PDF Hash Extractor.
- Uploaded the protected PDF.
- Copied the generated hash, which started with `$pdf$`.

Website: https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

**Step 3: Saving and Loading the Hash**

- Opened Notepad and pasted the extracted hash.
- Saved the file as `hash1.txt`.
- Opened Johnny and selected **Open password file**.
- Browsed to the saved text file and loaded the hash.

**Step 4: Recovering the Password**

- Selected **Start new attack** in Johnny.
- John the Ripper started testing possible password candidates against the extracted hash.
- Waited for the process to complete.
- Retrieved the recovered password displayed in Johnny.

**Step 5: Verifying the Recovered Password**

Opened the original protected PDF and entered the recovered password. The document opened successfully, confirming that the password recovery process was successful.

### Screenshots – Module 1

The following screenshots show the main stages of my practical work:

**1. Setting up Johnny GUI**

This screenshot shows the Johnny setup and configuration with the John the Ripper executable.

<img width="867" height="682" alt="image" src="https://github.com/user-attachments/assets/46348455-c7ca-4ce0-b433-a8c274289577" />

**2. Recovering the PDF Password**

This screenshot shows the password recovery result after running the attack using Johnny.

<img width="865" height="682" alt="image" src="https://github.com/user-attachments/assets/431631e4-32e2-4329-b850-ddf302abbc67" />


**3. Successfully Unlocked PDF**

This screenshot shows the original PDF after entering the recovered password.

<img width="495" height="697" alt="image" src="https://github.com/user-attachments/assets/ca073c7c-86ea-4823-ae70-25311d2a6aaa" />

---

## 4. Module 2 – Password Cracking with Networkwalks Tools

### Overview

For the second task, I used the online tools provided by Networkwalks to extract a PDF hash and retrieve the corresponding password.

Unlike the first module, this activity did not require installing a password-cracking application. The complete process was carried out through a web browser on Windows.

### Steps Performed

**Step 1: Accessing the Networkwalks Hash Calculator**

Opened the Networkwalks Hash Calculator in the web browser.

Website: https://networkwalks.com/hash-calculator/

**Step 2: Generating the PDF Hash**

- Downloaded the assigned protected PDF file, `My Locked PDF1.pdf`, from the Networkwalks lab page.
- Selected the PDF option in the Hash Calculator.
- Uploaded the protected document.
- Allowed the tool to process the file.
- Copied the generated hash value starting with `$pdf$`.

This hash was required for the next stage of the task.

**Step 3: Opening the Networkwalks Password Cracker**

Opened the Networkwalks Password Cracker in the browser.

Website: https://networkwalks.com/password-cracker/

**Step 4: Retrieving the Password**

- Pasted the complete extracted hash into the Password Cracker.
- Started the password attack.
- Waited while the tool tested possible password candidates.
- Retrieved the password displayed after a successful match.

**Step 5: Verifying the Password**

Opened the original protected PDF and entered the recovered password. The PDF opened successfully, confirming that the password had been retrieved correctly.

### Screenshots – Module 2

The following screenshots highlight the three main results from this task:

**1. PDF Hash Generation**

This screenshot shows the Networkwalks Hash Calculator generating the password-related hash from the protected PDF.

<img width="1127" height="846" alt="image" src="https://github.com/user-attachments/assets/ab882527-28f8-4d70-9bb1-8bf9cdafba5c" />

**2. Password Retrieved Successfully**

This screenshot shows the password recovery result displayed by the Networkwalks Password Cracker.

<img width="1107" height="872" alt="image" src="https://github.com/user-attachments/assets/80e627b9-732f-4d68-9645-9750375284a7" />

**3. Successfully Unlocked PDF**

This screenshot shows the protected PDF opened successfully using the recovered password.

<img width="560" height="787" alt="image" src="https://github.com/user-attachments/assets/e248d6ea-bb2f-4721-9336-ed0197728a63" />

---

## 5. Comparison of Both Modules

Both modules focused on recovering passwords from protected PDF files, but the tools and methods used were different.

| **Feature** | **Module 1 – John the Ripper** | **Module 2 – Networkwalks Tools** |
|---|---|---|
| Main Tool | John the Ripper | Networkwalks Password Cracker |
| Interface | Johnny GUI | Web browser |
| Hash Extraction | Online Hash Crack | Networkwalks Hash Calculator |
| Setup | Software installation required | No separate installation required |
| Hash Input | Text file (`hash1.txt`) | Directly pasted into the website |
| Password Recovery | Through John the Ripper | Through Networkwalks Password Cracker |
| Verification | Opened the protected PDF | Opened the protected PDF |

---

## 6. Key Observations

- A protected PDF's password-related hash can be extracted and used for password auditing.
- The extracted hash is not the actual password; it is used to test possible password candidates.
- John the Ripper works with compatible hash formats to perform password attacks.
- Johnny provides a convenient graphical interface for managing John the Ripper.
- Dictionary attacks work by testing a list of possible passwords.
- Networkwalks tools make hash extraction and password recovery possible directly through a browser.
- Testing the recovered password on the original PDF is important to confirm that the process worked.

---

## 7. What I Learned

This week's practical activities helped me understand password security beyond just the theory.

Some of the main things I learned were:

1. How password protection works in PDF documents.
2. How to extract a PDF hash using online tools.
3. How to install and configure John the Ripper with Johnny GUI on Windows.
4. How dictionary-based password attacks work.
5. How to use Networkwalks tools for hash generation and password recovery.
6. How to verify a recovered password by opening the original document.
7. Why strong and unpredictable passwords are important for protecting files.

---

## 8. Security Recommendations

Based on these activities, a few important password security practices are worth following:

- Use long and unique passwords for important documents.
- Avoid common words, names, dates, and predictable combinations.
- Do not reuse passwords across different files and accounts.
- Use suitable encryption settings when protecting sensitive PDFs.
- Store passwords securely.
- Carry out password auditing only on files you own or have permission to test.

---

## 9. Conclusion

Week 03 was a useful hands-on experience in understanding PDF password security and the tools used for password auditing.

In the first module, I worked with John the Ripper and Johnny GUI to extract a PDF hash, perform a password attack, and recover the document password.

In the second module, I used the Networkwalks Hash Calculator and Password Cracker to generate a hash and retrieve the password through an online process.

Completing both tasks on Windows gave me practical exposure to two different approaches to password recovery. More importantly, I understood how easily weak passwords can be tested and why choosing strong passwords matters when protecting important documents.

---

## 10. Disclaimer

This repository documents practical activities completed for educational purposes as part of the Networkwalks Cybersecurity Internship.

All exercises were performed using the training files and resources provided for the assigned tasks. These techniques should only be used on files you own or have explicit permission to test.

---

## 11. Author Information

**Alby John**

Cybersecurity & Ethical Hacking Intern | Networkwalks

| **Detail** | **Information** |
|---|---|
| Internship | Networkwalks |
| Week | 03 |
| Domain | Cybersecurity & Ethical Hacking |
| Topic | PDF Password Cracking & Hash Extraction |
| Operating System | Windows |

**Repository Purpose:** To document the Week 03 practical tasks, tools used, password recovery process, screenshots, and key learnings.
