\---

title: Medical Record Management Assistant

\---



A private, offline desktop app for storing medical records and preparing Release of Information (ROI) paperwork without sending your data to the cloud.



\*\*Your data stays on your computer, encrypted, and under your control.\*\*



> \*\*Status: MVP (In Development).\*\* This is an early release. Core features work, but the app is still evolving, feedback and bug reports are welcome via \[GitHub Issues](https://github.com/Lilian-Moon11/medical-record-management-assistant/issues).



\## Download



\*\*\[Download for Windows (.exe)](https://github.com/Lilian-Moon11/medical-record-management-assistant/releases/download/v1.0.0/Medical.Record.Management.Assistant.exe)\*\*



No installation or setup required - just download and run. The app creates its secure database automatically the first time you open it.



\*\*Mac and Linux users:\*\* a packaged app isn't available yet, but you can run the app from source today. See \[Running from Source](#running-from-source-mac--linux--advanced-windows) below.



\## What This App Does



\- Store medical documents (PDFs, records, reports) securely on your computer

\- Organize records by patient profile

\- Automatically extract clinical information (like conditions or medications) from scanned documents using a completely offline, local AI pipeline

\- Open documents when you need them, without permanently decrypting them

\- Help prepare Release of Information (ROI) paperwork

\- Export and import your data freely — no vendor lock-in

\- Work entirely offline — no internet connection required



\## Getting Started (Windows)



1\. Click the download link above

2\. Once downloaded, double-click \*\*Medical Record Management Assistant.exe\*\* to open it

3\. On first launch, you'll be asked to create a \*\*database password\*\* — this protects all your records

4\. The app will walk you through saving a \*\*recovery key\*\*. Save it somewhere safe (a password manager or a printed copy works well)

5\. That's it — you're in. Start adding patient profiles and documents whenever you're ready



\## Please Read: About Your Password and Recovery Key



This is important, so it's worth repeating here as well as in the app itself.



\- Your password is \*\*never stored anywhere\*\* — not by the app, not by the developer

\- If you lose \*\*both\*\* your password \*\*and\*\* your recovery key, your data \*\*cannot be recovered\*\*, by anyone



This is intentional. It's what keeps your medical information private and inaccessible to anyone but you. Please store your recovery key somewhere safe before adding sensitive information.



\## Privacy at a Glance



\- \*\*Runs only on your computer.\*\* Nothing is uploaded anywhere. No servers, no accounts.

\- \*\*Strong encryption.\*\* Records are encrypted with industry-standard methods (AES-256 via SQLCipher). Without your password, the data is unreadable.

\- \*\*No cloud syncing, ever.\*\* Your files never leave your device unless you move them yourself.

\- \*\*Built with accessibility in mind\*\*, including keyboard navigation and screen-reader support.



\## System Requirements



\- \*\*Windows\*\* — no additional setup needed, just the `.exe`

\- \*\*Mac / Linux\*\* — currently requires running from source (see below); a packaged version is planned



\## Running from Source (Mac / Linux, or advanced Windows use)



This is more technical — you'll need some comfort with the command line.



\*\*Requirements:\*\* Python 3.12 (required for the local AI/OCR features)



```bash

git clone https://github.com/Lilian-Moon11/medical-record-management-assistant.git

cd medical-record-management-assistant

```



Create a virtual environment (recommended):



```bash

\# Mac / Linux

python3.12 -m venv .venv

source .venv/bin/activate

```

```bash

\# Windows

py -3.12 -m venv .venv

.\\.venv\\Scripts\\activate

```



Install dependencies and run:



```bash

pip install -r requirements.txt

python main.py

```



Full setup details and troubleshooting live in the \[project README](https://github.com/Lilian-Moon11/medical-record-management-assistant).



\## Source Code \& License



This project is open source, licensed under the \[GNU AGPLv3](https://github.com/Lilian-Moon11/medical-record-management-assistant/blob/main/LICENSE).



\[View the full source code and README on GitHub →](https://github.com/Lilian-Moon11/medical-record-management-assistant)



Questions or issues? \[Open an issue on GitHub](https://github.com/Lilian-Moon11/medical-record-management-assistant/issues).

