# 🛡️ Penetration testing Lab

Welcome to my local Penetration Testing Lab repository. This space contains the configuration files, custom scripts, and documentation used to build and maintain my isolated environment for practicing offensive security techniques.

This lab is designed to safely simulate real-world vulnerabilities, test custom exploits, and practice methodologies for web exploitation and Capture The Flag (CTF) challenges without exposing external networks.

---

## 🏗️ Lab Architecture

The environment consists of an attacker machine and various intentionally vulnerable target systems isolated on a private virtual network.

*   **Attacker Machine:** Kali Linux / Parrot OS (Running locally or via VM)
*   **Target Environments:**
    *   Dockerized web applications (for practicing OWASP Top 10, JWT manipulation, and command injection).
    *   Isolated virtual machines (e.g., Metasploitable, vulnerable Linux/Windows boxes).
    *   Custom vulnerable sandboxes designed to test specific exploit chains.

---

## 📂 Repository Structure

```text
offensive-security-lab/
├── Setup/                  # Vagrantfiles, Docker Compose files, and provisioning scripts
├── Custom-Targets/         # Source code for intentionally vulnerable apps and local challenges
├── Exploits-and-Scripts/   # Python automation scripts and custom C payload generators
├── Wordlists/              # Custom compiled dictionaries and fuzzing lists
└── Lab-Notes/              # Network maps, configuration details, and attack methodologies
