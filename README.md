# COMP3134 – Cybersecurity Labs (Winter 2026)

This repository contains weekly lab exercises and resources for the COMP3134 Winter 2026 course, with a focus on practical **cybersecurity** concepts and hands-on skills.  
It is organized by week to match the course outline and in-class activities.

---

## Repository structure

Each folder corresponds to a specific week of the course and contains lab instructions, scripts, configuration files, and supporting artifacts (such as screenshots or sample data).

```text
comp3134Winter2026/

├── wk1/   # Week 1 labs
├── wk2/   # Week 2 labs
├── wk4/   # Week 4 labs
├── wk5/   # Week 5 labs
├── wk9/   # Week 9 labs
├── wk10/  # Week 10 labs (with screenshots)
├── wk12/  # Week 12 labs – CSRF/XSS materials
└── wk13/  # Week 13 labs – SQL vulnerabilities
```

> Note: Week numbers follow the course schedule; some weeks may be reserved for midterms, holidays, or project work and therefore have no folder.

---

## Goals of the labs

The labs in this repository are designed to help you:

- Build a **practical** understanding of fundamental cybersecurity concepts such as threats, vulnerabilities, and security controls.  
- Gain hands-on experience with common security tools, scripts, and network or application configurations.  
- Practice secure configuration, basic system hardening, monitoring, and incident-style analysis.  
- Develop troubleshooting and documentation skills using clear notes, screenshots, and lab reports (for example, in `wk10` and later weeks).

---

## How to use this repository

1. **Clone the repository**  
   ```bash
   git clone https://github.com/uzmashxxxikh/comp3134Winter2026.git
   cd comp3134Winter2026
   ```

2. **Navigate to the appropriate week**  
   ```bash
   cd wk1
   # or wk2, wk4, wk5, wk9, wk10, wk12, wk13
   ```

3. **Read the lab instructions**  
   - Look for `README` files, `instructions` documents, or PDF/Word lab sheets in each week’s folder.  
   - Review scripts, configuration files, and screenshots to understand the tasks and expected outcomes for that lab.

4. **Run the labs in a safe environment**  
   - Follow any setup notes in the week’s folder (required tools, operating system, virtual machines, etc.).  
   - Only run security-related scripts and commands in an isolated environment (e.g., VMs or lab machines), not on your primary host system.

---

## Prerequisites

To work effectively with these labs, you should be comfortable with:

- Basic command-line usage (Linux and/or Windows PowerShell/Command Prompt).  
- Installing and using development and security tools such as terminals, IDEs, virtualization platforms, and packet or log analysis tools.  
- Reading and modifying configuration files and simple scripts.

Your instructor may provide additional requirements, such as a specific Linux distribution, preconfigured virtual images, or access to the college lab environment.

---

## Academic integrity

This repository is intended for **learning and reference** only.

- Do not submit someone else’s work or this repository’s contents as your own graded assignment.  
- If you reuse code or configurations from this repo, make sure you truly understand them and follow all course and institutional policies.  
- Collaboration is encouraged for learning, but always write your own solutions and lab reports.

---

## Contributing and updates

If you are the course instructor or a student maintaining your own fork:

- Add new weekly lab folders as the course progresses (e.g., `wk6`, `wk7`).  
- Commit new or updated lab files with clear messages such as `Add Week 9 DoS lab` or `Update wk12 CSRF screenshots`.  
- Avoid committing sensitive information such as passwords, private keys, or personal data.

Example workflow:

```bash
git add wk12
git commit -m "Add wk12 lab files"
git push origin main
```

---

## License / usage

Unless otherwise specified by the instructor, this repository is for educational use within the COMP3134 Winter 2026 course.  
Check with your instructor before reusing material outside the course or publishing your own public copy based on this work.

---

## Contact

For any questions about these labs or how to set up your environment:

- Refer to your course syllabus and LMS (e.g., eConestoga, Brightspace, Blackboard) for official contact details.  
- Ask your instructor or TA if you are unsure how to complete a lab or safely run cybersecurity exercises.

If you want to customize this README, you can add a short topic description under each `wk*` folder (for example: `wk4 – Network traffic analysis with Wireshark`, `wk9 – DoS concepts`, `wk12 – CSRF/XSS`, `wk13 – SQL injection`).
