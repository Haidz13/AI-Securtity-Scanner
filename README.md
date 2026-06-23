# AI-Securtity-Scanner

Gemini Python Security Scanner
An intelligent, command-line security tool that leverages the Gemini API to instantly audit and detect vulnerabilities in Python source code. Instead of manually searching for security flaws, this tool automates the process to catch critical issues in seconds.

⚡ Features & Capabilities
This scanner analyzes your Python files and leverages AI to spot common security risks, including:

SQL Injection: Identifies unsanitized user inputs interacting dangerously with databases.

Hardcoded Secrets: Catches exposed API keys, credentials, and tokens before they get pushed to production.

Weak Cryptography: Spots the use of outdated, broken, or insecure encryption algorithms.

⚙️ How It Works
The architecture of the scanner is designed to be lightweight, efficient, and terminal-friendly:

Trigger: The user runs the tool via the terminal and passes a Python file for analysis.

Ingestion: The scanner.py script reads the local file contents.

AI Audit: The script securely calls the Gemini API to analyze the code for vulnerabilities.

Report: scanner.py receives the raw analysis, formats it for optimal readability, and prints the security report directly back to the user's terminal.
