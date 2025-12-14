🔐 HASHIFY – File Integrity Verifier

HASHIFY is a secure file integrity verification system that uses SHA-256 cryptographic hashing to detect file tampering. It generates a unique hash for a file and verifies authenticity by comparing hash values. Even the smallest modification results in a completely different hash, ensuring reliable integrity checks.

🚀 Features

SHA-256 based secure hashing

Single-file integrity verification

Detects file tampering and corruption

Export verification reports in TXT and JSON formats

Modular backend architecture

GUI-ready design for future enhancement

🛠️ Tech Stack

Language: Python

Hash Algorithm: SHA-256

GUI: Tkinter (integration ready)

Report Formats: .txt, .json 
HASHIFY/
├── file_reader.py
├── hash_generator.py
├── hash_verifier.py
├── report_saver.py
├── utils.py
├── main.py
├── multi_file_gui.py
└── README.md
▶️ How to Run
cd hashify-frontend
npm install
npm start
