# Insecure Data Storage in Android Apps 🔐

This is my MSc Cybersecurity dissertation project investigating insecure data storage issues in open-source Android apps using static and dynamic analysis tools.

## 🧪 Project Summary
- Analyzed 10 open-source Android apps from F-Droid and GitHub
- Used MobSF (static + dynamic), ADB shell, and Genymotion emulators
- Identified common vulnerabilities: plaintext storage, insecure SQLite databases, exposed logs
- Mapped to Android architecture layers and CVSS-style severity

## 🧰 Tools Used
- MobSF (Mobile Security Framework)
- ADB (Android Debug Bridge)
- Genymotion / Android Emulator
- OWASP MSTG

## 📁 Folder Structure
- `/Static Analysis Reports/` → PDF reports of each app scanned with MobSF
- `/Images of Dynamic Analysis/` → Screenshots of ADB inspection and runtime issues
- `/Lab Setup Images/` → Emulator setup, tool config, proof of testing environment
- `List of 10 Apps Analysis Performed.pdf` → App names, categories, basic details

## 📸 Screenshots
![MobSF Sample Output](Lab setup Images/mobsf-login.jpg)
![GenyMotion Emulator](Lab setup Images/genymotion.jpg)


## 🛡️ License
MIT

## 💬 Contact
For academic/collaborative interest: mansi.official.1706@gmail.com
