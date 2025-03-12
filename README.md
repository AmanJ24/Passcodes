# OverTheWire Wargames Solutions 🎮🔐

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Security](https://img.shields.io/badge/Security-FF0000?style=for-the-badge&logo=hackaday&logoColor=white)

## Description 📝

This repository contains my personal solutions, notes, and approaches for various [OverTheWire](https://overthewire.org/wargames/) wargames challenges. These wargames help in learning and practicing security concepts in a fun and challenging way.

> **Note**: These are my personal notes and solutions. I recommend trying to solve the challenges yourself before looking at any solutions!

## Table of Contents 📋

- [Bandit](#bandit)
- [Krypton](#krypton)
- [Leviathan](#leviathan)
- [Natas](#natas)
- [Setup & Usage](#setup--usage)
- [Security Note](#security-note)

## Wargames Overview 🏆

### Bandit

Bandit is aimed at absolute beginners. It teaches the basics of many common Unix utilities and is a great starting point for those new to Linux and command line environments. The challenges cover skills like:

- Basic Linux commands
- File permissions
- Data encoding/decoding
- Shell scripting
- Network protocols (SSH, HTTP, etc.)

[Bandit Solutions →](./bandit)

### Krypton

Krypton focuses on teaching cryptography principles through increasingly challenging encryption puzzles. Players learn about:

- Basic cryptographic techniques
- Substitution ciphers
- XOR encryption
- Frequency analysis
- Cryptanalysis methods

[Krypton Solutions →](./krypton)

### Leviathan

Leviathan is a small wargame with few levels but requires careful reverse engineering and problem-solving skills. It focuses on:

- Binary analysis
- Privilege escalation
- Executable permissions
- Linux security concepts

[Leviathan Solutions →](./leviathan)

### Natas

Natas teaches the basics of serverside web security. Each level contains a vulnerability that must be exploited to gain access to the next level. Challenges include:

- Basic web security concepts
- SQL injection
- Session management
- Server-side request forgery
- File inclusion vulnerabilities
- Cross-site scripting (XSS)

[Natas Solutions →](./natas)

## Setup & Usage 🛠️

To use this repository effectively:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/overthewire-solutions.git
   cd overthewire-solutions
   ```

2. Navigate to the specific wargame directory you're interested in:
   ```bash
   cd bandit
   ```

3. Read the level solutions in numerical order. Each level typically includes:
   - The challenge description
   - My approach to solving it
   - The commands used
   - The password obtained (if applicable)

4. For SSH-based challenges, you can connect using:
   ```bash
   ssh username@hostname -p port
   ```

## Security Note ⚠️

This repository may contain private keys and passwords used in the OverTheWire challenges. These are shared for educational purposes only. Please:

- **DO NOT** use any private keys found here for your personal accounts
- **DO NOT** reuse passwords found in this repository
- Remember that storing credentials in a public repository is generally a security risk

## Disclaimer

The solutions are provided for educational purposes only. Use them responsibly and prioritize learning over simply finding answers.

Happy hacking! 👨‍💻

