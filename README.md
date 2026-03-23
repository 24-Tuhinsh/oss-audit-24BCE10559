# Open Source Audit Project - 24BCE10559

**Student Name:** Tuhinsh Sharma  
**Roll Number:** 24BCE10559  
**GitHub Username:** 24-Tuhinsh  
**Project:** Open Source Audit  
**Chosen Software:** [Specify your software, e.g., Apache HTTP Server]  

---

## Project Overview

This repository contains five shell scripts developed as part of the **Open Source Audit** project for the OSS NGMC course at VITyarthi.  
The scripts demonstrate practical Linux skills and illustrate understanding of open-source software, its philosophy, and system interactions.

---

## Scripts

### 1. **System Identity Report** (`script1.sh`)
- **Purpose:** Displays basic Linux system information such as distribution, kernel version, current user, uptime, and license message.
- **Concepts:** Variables, `echo`, command substitution `$(...)`, basic output formatting.
- **Run:**
  ```bash
  ./script1.sh
2. FOSS Package Inspector (script2.sh)
Purpose: Checks if the chosen open-source software is installed, shows version and license, and provides a brief description of the package.

Concepts: if-then-else, case statement, rpm/dpkg, pipes with grep.

Run:

./script2.sh [package_name]
Default package can be provided as an argument.

3. Disk and Permission Auditor (script3.sh)
Purpose: Loops through important system directories and reports owner, permissions, and disk usage.

Concepts: for loop, ls -ld, du -sh, awk.

Run:

./script3.sh
4. Log File Analyzer (script4.sh)
Purpose: Reads a log file line by line, counts occurrences of a keyword, and shows the last 5 matching lines.

Concepts: while-read loop, if-then, counters, command-line arguments $1, $2.

Run:

./script4.sh /path/to/logfile [keyword]
Default log file: /var/log/syslog, default keyword: error.

5. Open Source Manifesto Generator (script5.sh)
Purpose: Interactively generates a personalized open-source philosophy statement based on user inputs.

Concepts: read for input, string concatenation, writing to a file, date command.

Run:

./script5.sh
How to Run All Scripts
Clone the repository:

git clone https://github.com/24-Tuhinsh/oss-audit-24BCE10559.git
cd oss-audit-24BCE10559
Make scripts executable (if not already):

chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
Run any script as needed:

./script1.sh
./script2.sh apache2
./script3.sh
./script4.sh /var/log/syslog error
./script5.sh
Notes
Ensure you have the necessary permissions for accessing system directories and log files. Use sudo if required.

Scripts are tested on Ubuntu WSL environment; minor adjustments may be needed for other Linux distributions.

The report PDF for the Open Source Audit project must be submitted along with this repository link on the VITyarthi portal.

Submitted by: Tuhinsh Sharma (24BCE10559)
Date: March 2026

