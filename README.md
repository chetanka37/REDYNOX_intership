Redynox Cyber Security Internship – Task 1
===============================================================
README – Final Submission Report for Task 1 (Network Security Basics)
===============================================================

🎯 OBJECTIVE OF THE TASK:
----------------------------
To understand and apply fundamental network security concepts using only Kali Linux.  
This task helps beginners get hands-on experience with real-world tools and threats by:

- Learning about common network attacks
- Simulating traffic (ICMP, DNS, HTTP)
- Capturing & analyzing packets using Wireshark
- Practicing firewall setup using UFW
- Documenting all findings and submitting to GitHub

---

🛠️ TOOLS USED:
-----------------
| Tool              | Purpose                                 |
|-------------------|------------------------------------------|
| Kali Linux        | Operating system for ethical hacking     |
| Terminal          | Running Linux commands                   |
| Firefox           | To create HTTP and DNS traffic           |
| Wireshark         | Packet capture and traffic analysis      |
| UFW               | Firewall configuration and simulation    |
| nano              | Command-line text editor for notes       |
| gnome-screenshot  | For capturing proof of work              |
| Git & GitHub      | For submitting project online            |

---

🧪 METHODS USED:
------------------
- Researched network threats and security techniques
- Wrote structured `.txt` reports and markdown notes
- Used tools like `ping`, `ufw`, Wireshark, Firefox
- Simulated and analyzed network traffic
- Documented process with screenshots
- Uploaded complete work to GitHub for review

---

📋 TASK STEPS FOLLOWED:
-------------------------

• Researched and documented common network threats:
  - Viruses, Worms, Trojans, Phishing, DDoS, MITM, Packet Sniffing  
  - Saved in `notes/day1_network_threats.md`

• Learned core security concepts:
  - Firewalls (UFW), WPA2/WPA3 encryption, strong password policies  
  - Installed and configured UFW:
    ```bash
    sudo apt install ufw
    sudo ufw enable
    sudo ufw allow 22
    sudo ufw allow 80
    sudo ufw deny 21
    ```

• Simulated real traffic:
  - `ping google.com` to generate ICMP
  - Browsed `http://testphp.vulnweb.com` to generate HTTP and DNS

• Captured and analyzed network traffic in Wireshark:
  - Applied protocol filters: `icmp`, `dns`, `http`
  - Captured screenshots using:
    ```bash
    gnome-screenshot -f screenshots/task1_icmp.png
    ```

• Wrote clear summaries:
  - Observed IPs, GET requests, DNS resolutions, ICMP echo/reply
  - Saved all findings in `.txt` files inside the `notes/` folder

• Uploaded full folder to GitHub using:
    ```bash
    git init
    git add .
    git commit -m "Task 1 - Network Security Completed"
    git remote add origin https://github.com/<your-username>/Task1_NetworkSecurity.git
    git branch -M main
    git push -u origin main
    ```

---

⚠️ CHALLENGES FACED AND HOW I SOLVED THEM:
--------------------------------------------

1. **Wireshark not showing ICMP**  
   ✅ Solved by choosing correct interface (eth0) and running live `ping` during capture.

2. **Firefox showing proxy errors**  
   ✅ Fixed by setting “No Proxy” in browser settings.

3. **No WiFi encryption check inside VirtualBox**  
   ✅ Noted that WPA2/WPA3 can’t be checked without an external Wi-Fi adapter in VM.

4. **GitHub CLI asking for password**  
   ✅ Generated GitHub token and used it instead of password for pushing.

5. **Confusion with Linux commands as a beginner**  
   ✅ Followed step-by-step terminal instructions and saved all notes clearly.

---

📂 FINAL FOLDER STRUCTURE:
---------------------------


---

📈 RESULTS AND OUTCOMES:
---------------------------
✅ Understood basic types of cyber threats and network attacks  
✅ Learned firewall configuration using UFW  
✅ Successfully simulated ICMP, DNS, and HTTP traffic  
✅ Captured and analyzed live packets in Wireshark  
✅ Created detailed reports and documentation  
✅ Pushed complete task folder to GitHub for certification

---

🚀 STATUS:
-----------
✅ Task 1 Fully Completed  
📤 Ready for Redynox certificate verification  
🔗 GitHub link shared for review  
📝 All `.txt` and `.png` files included with proper structure

---

📢 HOW OTHERS CAN USE THIS PROJECT TO PRACTICE:
--------------------------------------------------
- Use Kali Linux inside VirtualBox  
- Follow all steps in this README  
- Write your own `.txt` summaries and save screenshots  
- Analyze network packets using Wireshark  
- Upload your own version to GitHub  
- Share with mentors or on LinkedIn as your learning proof

---

End
