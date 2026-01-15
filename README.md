Project legoIV 🧱
Project legoIV is a portable Windows utility that combines a custom Graphical User Interface (GUI) with Text-to-Speech (TTS) technology. It is designed to help users retrieve system specifications and understand PC optimization through an interactive, guided experience.

🚀 Key Features
Interactive Voice Assistants: Features two digital personalities, Zira and David, who explain the project’s safety, origin, and functionality using real-time audio.

One-Click System Diagnostics: Instantly runs a deep scan of hardware and software specs using the Windows systeminfo engine.

Automatic Report Generation: Exports spec data into a text file and automatically launches it in Notepad for immediate viewing.

Themed Interface: A specialized "Matrix-style" Dark Green and Black UI designed for clarity and a tech-focused aesthetic.

Standalone Executable: Compiled as a portable .exe—no Python installation or library setup required for the end-user.

🖥 Usage Instructions
1. Installation
Download the latest legoIV.exe from the Releases section.

Place the executable in its own folder (it creates a temporary text file when generating reports).

2. Running the App
Double-click legoIV.exe to launch.

Note: Because the app is an independent project, you may see a Windows "SmartScreen" popup. Click "More Info" and then "Run Anyway" to start the assistant.

3. Controls
Interaction: Click the gray buttons to hear David and Zira discuss different topics.

Generate Info: Click "Get System Info". A command window will briefly process the request, and Notepad will open automatically with your details.

Safe Exit: Use the red "Exit APP" button to shut down the voice engine and the interface safely.

🛡 Safety & Security Guidelines
We prioritize user transparency and system integrity:

Read-Only Operations: The "System Info" tool is non-invasive. It only reads data; it does not modify your BIOS, Registry, or system files.

Local Data Privacy: All generated information stays on your computer in sys_info_temp.txt. No data is ever transmitted to external servers.

Open Source: You can verify every line of code in the legoIV.py file in this repository to ensure the software's safety.

🛠 Troubleshooting
"Windows Protected Your PC" Warning
As an independent open-source project, this .exe is not digitally signed by a major corporation. Windows flags all new, unsigned files as a precaution. This is expected behavior.

Solution: Click More Info -> Run Anyway.

Antivirus "False Positives"
Some antivirus programs (like Windows Defender) might flag executables made with Python. This is a common "False Positive."

Verification: You are encouraged to review the source code here on GitHub to confirm the app's safety.

Fix: Add an "Exclusion" for legoIV.exe in your antivirus settings if it prevents the app from running.

System Info Not Displaying
If Notepad does not open, ensure you have Write Permissions in the folder where the .exe is located. Try moving the app to your Desktop or a dedicated folder.

🤝 Contributing
Since this project is open source, contributions are welcome!

Fork the project.

Create your feature branch.

Submit a Pull Request for review.

Author: Ollie

License: MIT (Recommended)
