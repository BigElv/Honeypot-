# Honeypot

 Setting Up a Honeypot with PentBox in Kali Linux

1. Install Ruby (required to run PentBox):

   sudo apt update
   sudo apt install ruby

2. Download PentBox from GitHub:

   git clone https://github.com/technicaldada/pentbox.git
   cd pentbox

3. Run PentBox:

   ruby pentbox.rb

4. Navigate the menu:

   Select `3` → Faking stuff

    Then `2` → Honeypot

6. Configure the honeypot:

 Choose a port number (e.g., 23 for Telnet)

Enter a log file path (e.g., `/home/kali/Desktop/honeypot.log`)

Set a warning message (e.g., "Unauthorized access is prohibited!")

6. Let it run:

   PentBox will listen on the selected port and log all connection attempts.

7. Check logs:

   cat /home/kali/Desktop/honeypot.log


