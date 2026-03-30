# OSS_Project

# Open Source Audit: VLC Media Player
**Course:** OSS NGMC | [cite_start]Unit Coverage 1-5 [cite: 5]
[cite_start]**Student Name:** [Your Name] [cite: 6]
[cite_start]**Registration Number:** [Your Reg No] [cite: 6]

---

## 1. Project Overview
[cite_start]This project is a structured audit of **VLC Media Player**, a real open-source software project that can be interacted with on Linux[cite: 12]. [cite_start]The audit covers its origin story, licensing, and practical footprint on a Linux system[cite: 13, 66].

### Why VLC?
[cite_start]VLC was chosen because it was built by students in Paris who wanted to stream video over a university network when no free tool existed[cite: 24, 40]. [cite_start]It is a perfect example of a community-driven project that "plays anything".

---

## 2. Shell Script Suite
[cite_start]This repository contains five functional Bash scripts that demonstrate practical Linux skills and automation[cite: 14, 15].

| File | Description | [cite_start]Key Concepts [cite: 99, 128, 148, 166, 188] |
| :--- | :--- | :--- |
| `script1.sh` | [cite_start]**System Identity Report**: Displays kernel, user, and uptime[cite: 93]. | Variables, `echo`, Command Substitution. |
| `script2.sh` | [cite_start]**FOSS Package Inspector**: Checks if VLC is installed and prints its philosophy[cite: 125]. | `if-then-else`, `case` statements, `grep`. |
| `script3.sh` | [cite_start]**Disk & Permission Auditor**: Reports on directory sizes and ownership[cite: 145]. | `for` loops, `ls`, `awk`/`cut`. |
| `script4.sh` | [cite_start]**Log File Analyzer**: Counts keywords like ERROR in a log file[cite: 163]. | `while-read` loop, counters, arguments. |
| `script5.sh` | [cite_start]**OSS Manifesto Generator**: Creates a personalized philosophy statement[cite: 185]. | `read` input, file redirection, `date`. |

---

## 3. How to Run
1. [cite_start]Ensure you are in a Linux environment or using Git Bash on Windows[cite: 92].
2. Grant execution permissions to the scripts:
   ```bash
   chmod +x *.sh
   