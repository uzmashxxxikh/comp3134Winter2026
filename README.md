Here is an overall README you can put at the root of your repo for a cybersecurity-focused COMP3134 Winter 2026 course.

```markdown
# COMP3134 – Cybersecurity Labs (Winter 2026)

This repository contains weekly lab exercises and resources for the **COMP3134 Winter 2026** course, focused on practical cybersecurity concepts and skills.[page:1] It is organized by week to match the course outline and classroom activities.

---

## Repository Structure

Each folder corresponds to a specific week of the course and contains lab instructions, scripts, configuration files, and screenshots where applicable.[page:1]

```text
comp3134Winter2026/
├── wk1/   # Week 1 labs
├── wk2/   # Week 2 labs
├── wk4/   # Week 4 labs
├── wk5/   # Week 5 labs
├── wk9/   # Week 9 labs
├── wk10/  # Week 10 labs (with screenshots)
├── wk12/  # Week 12 labs
└── wk13/  # Week 13 labs
```

> Note: Week numbers are based on the course schedule; not every week may have a separate folder (e.g., midterms, holidays, or project work).[page:1]

---

## Goals of the Labs

The labs in this repository are designed to help you:

- Build a **practical** understanding of fundamental cybersecurity concepts (e.g., threats, vulnerabilities, and controls).
- Gain hands-on experience with security tools, scripts, and configurations.
- Practice secure configuration, basic hardening, monitoring, and incident analysis.
- Develop troubleshooting and documentation skills using screenshots and lab reports (for example, in `wk10` and later weeks).[page:1]

---

## How to Use This Repository

1. **Clone the repository**

   ```bash
   git clone https://github.com/zzaki13/comp3134Winter2026.git
   cd comp3134Winter2026
   ```

2. **Navigate to the appropriate week**

   ```bash
   cd wk1   # or wk2, wk4, wk5, wk9, wk10, wk12, wk13
   ```

3. **Read the lab instructions**

   - Look for `README`, `instructions`, or PDF/Word files in each week’s folder.
   - Review scripts, configuration files, and screenshots to understand what was done in that lab.

4. **Run labs in your environment**

   - Follow any setup notes included in the week’s folder (e.g., required tools, OS, or virtual machines).
   - Only run scripts and commands in a safe, isolated environment (e.g., virtual machines) to avoid impacting your host system.

---

## Prerequisites

To complete labs from this repo, you should be comfortable with:

- Basic command line usage (Linux and/or Windows PowerShell/Command Prompt).
- Installing and using development and security tools (IDEs, terminals, virtualization software, etc.).
- Reading and modifying configuration files and simple scripts.

Your instructor may provide additional requirements (e.g., specific Linux distribution, virtual lab image, or college lab environment).

---

## Academic Integrity

This repository is intended for **learning and reference**.

- Do not submit someone else’s work as your own.
- When using code or configurations from this repository for your assignments, make sure you understand what they do and follow your instructor’s policies.
- If you collaborate, always write your own solutions and lab reports.

---

## Contributing / Updating

If you are the course instructor or a student maintaining your own copy:

- Add new weekly lab folders as the course progresses (e.g., `wk6`, `wk7`).
- Commit lab files with clear messages such as `Add Week X lab` or `Update Week X screenshots`.[page:1]
- Keep sensitive information (passwords, private keys, personal data) out of the repository.

Example:

```bash
git add wk12
git commit -m "Add wk12 lab files"
git push origin main
```

---

## License

Unless otherwise specified by the instructor, this repository is for educational use within the COMP3134 Winter 2026 course.  
Check with your instructor before reusing material outside the course or making the repository public under your own account.

---

## Contact

For questions about the labs or repository:

- Refer to your **course syllabus** and **LMS (e.g., eConestoga/Brightspace/Blackboard)** for official contact details.
- Ask your instructor or TA if you are unsure how to complete a lab or set up the environment.

```

If you tell me what each week (wk1, wk2, wk4, etc.) specifically covers, I can customize the README to list the exact cybersecurity topics and tools used for each folder.
