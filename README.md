# 📞 AstraCalls - Clear WhatsApp voice calls on browsers

<a href="https://github.com/melodic-neurolinguist451/AstraCalls"><img src="https://img.shields.io/badge/Download-AstraCalls-blue" alt="Download AstraCalls"></a>

AstraCalls lets you make WhatsApp voice calls directly from your web browser. This tool helps you manage communication without keeping your phone nearby. It connects your browser to your WhatsApp account securely. You can handle messages and calls through a simple interface. Business owners and support teams use this to improve their workflow. It keeps your data organized in a local database.

## ⚙️ System Requirements

Before you start, ensure your computer meets these needs:

*   Operating System: Windows 10 or Windows 11.
*   Memory: At least 4GB of RAM.
*   Storage: 200MB of free disk space.
*   Network: A stable internet connection.
*   Browser: Google Chrome or Microsoft Edge.
*   Software: Docker Desktop for Windows.

## 📥 How to Install

Download the application from the official link below:

[https://github.com/melodic-neurolinguist451/AstraCalls](https://github.com/melodic-neurolinguist451/AstraCalls)

Follow these steps to get the software ready:

1.  Click the link above to reach the main page.
2.  Look for the green button labeled Code.
3.  Choose Download ZIP from the menu.
4.  Save the file to your computer.
5.  Right-click the folder and choose Extract All.
6.  Open the folder once the extraction finishes.

## 🚀 Setting Up the Software

AstraCalls requires Docker to function. Docker acts as a container for the application.

1.  Download and install Docker Desktop from the official Docker website if you do not have it.
2.  Restart your computer after the Docker installation.
3.  Open the Docker Desktop application and wait for the engine to start.
4.  Open your command prompt by clicking the Start menu, typing cmd, and pressing Enter.
5.  Type `cd` followed by a space and drag your AstraCalls folder into the window. Press Enter.
6.  Type `docker-compose up` and press Enter to start the services.
7.  Wait for the logs to stop scrolling. This indicates the system is ready.

## 🌐 Using the Interface

Once the setup process finishes, you can access the application through your web browser.

1.  Open Chrome or Edge.
2.  Type `localhost:8080` in the address bar.
3.  Press Enter to load the dashboard.
4.  Scan the QR code with your WhatsApp app on your phone.
5.  Your account will sync with the browser.

You now see your contact list and call records. Click on any contact to start a voice call or send a message.

## 📂 Managing Sessions

Each session saves your preferences and chat history in a local file. The software stores these files in the session folder inside your main AstraCalls directory. 

*   To clear your data, delete the session folder.
*   To start fresh, restart the Docker process after deleting the folder.
*   The software creates a new session file automatically when you scan the QR code again.

## 🛡️ Privacy and Security

AstraCalls stores all your data inside your local machine. No external servers capture your messages or voice data. Your WhatsApp data stays private. Always keep your browser updated to ensure the best security. Use a strong password if you enable the password protection feature in the settings menu.

## 🔧 Troubleshooting

If you encounter issues, try these steps:

*   Issue: The dashboard does not load.
    *   Solution: Check if Docker Desktop is running in your taskbar. Ensure no other application uses port 8080.
*   Issue: QR code does not appear.
    *   Solution: Refresh the browser page. Check your internet connection.
*   Issue: Calls drop frequently.
    *   Solution: Ensure your PC has a stable connection to your router. A wired connection works best.
*   Issue: Data does not save.
    *   Solution: Check if you have write permissions for the AstraCalls folder.

## 📈 Integration Features

AstraCalls includes tools for advanced users:

*   Chatwoot Integration: Connect your dashboard to your Chatwoot account for team collaboration.
*   Webhooks: Send automatic alerts to other services when you receive a message.
*   API Access: Use the built-in system to build your own plugins or tools.

Refer to the internal configuration files to enable these features. Edit the files with a standard text editor like Notepad. Save the files and restart the Docker container to apply changes.