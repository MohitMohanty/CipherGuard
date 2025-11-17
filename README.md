🔐 CipherGuard: Real-Time Password Entropy Analyzer

STATUS: ACTIVE | EXECUTION PROTOCOL: SUCCESS

🧭 PROJECT_GOAL

In an era where data breaches are widespread, weak passwords continue to be a major security risk. CipherGuard is built to empower users and developers by providing a rapid, fully client-side utility to evaluate password resilience.
Its mission: translate NIST password standards into a clear, terminal-style strength report, encouraging the use of strong, high-entropy passphrases.

🧪 ANALYSIS_OVERVIEW

CipherGuard is a fast, single-page web application that analyzes and scores password strength according to principles inspired by NIST SP 800-63B.

Instead of simple red/yellow/green indicators, CipherGuard generates a real-time, terminal-themed security assessment, offering immediate, actionable improvements.

⚙️ CORE_FEATURES
✅ NIST-Inspired Entropy Scoring

Calculates entropy using length + character-set diversity

Prioritizes passphrases 12+ characters

Uses 4 character classes:

lowercase

uppercase

numbers

symbols

This aligns with modern, complexity-balanced password guidance.

🚫 Breach Dictionary & Pattern Detection

CipherGuard applies strict penalties for:

Common dictionary words

Sequential patterns (123, abc)

Excessive repetition (aaaaa)

This reduces vulnerability to dictionary attacks, pattern attacks, and brute-force guessing.

⚡ Real-Time Composition Analysis

Displays a live [ COMPOSITION_CHECK ] table showing which character sets are:

[ USED ]

[ MISSING ]

This helps users immediately understand what to add for maximum entropy.

🗂️ Single-File Integrity

Built entirely using one self-contained HTML + TailwindCSS + JavaScript file.
No installs. No build steps. No dependencies.
Just open and run.

🖥️ Immersive Terminal Aesthetic

Dark theme • Neon-lime highlights • Monospace grid
A complete USER@CYPHER-NODE visual experience.

🚀 DEPLOYMENT
🔗 Live Demo

👉 https://mohitmohanty.github.io/CipherGuard/

📥 Clone the Repository
git clone https://github.com/mohitmohanty/CipherGuard

▶️ Run Locally

Just open the file:

index.html


in any modern browser.

⚠️ SECURITY WARNING

This tool is for educational and testing purposes only.
Never enter real production passwords into third-party tools, including this one.
