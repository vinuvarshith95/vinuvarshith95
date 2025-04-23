# 👋 Hi, I'm Vinu Varshith  
**SOC Analyst | Blue Team Enthusiast | Cybersecurity Explorer | Researcher**



## 🛡️ About Me

Hey there! I’m Vinu, a cybersecurity enthusiast with a strong foundation in blue teaming, threat detection, and incident response. I'm passionate about securing digital ecosystems and enjoy diving into logs, analyzing alerts, and building better defenses.

🔍 My focus areas:
- Security Operations Center (SOC) activities
- Threat hunting and log analysis
- SIEM tools (Splunk, ELK, Wazuh)
- IDS/IPS, endpoint monitoring, malware analysis
- Python scripting for automation & data parsing



## 🔬 Projects in Cybersecurity

### 🧪 Home SOC Lab – Splunk + Sysmon with Malware Simulation
- Built a SOC lab using VirtualBox with **Kali Linux (attacker)** and **Windows 11 (victim)**
- Installed **Sysmon** to collect Windows telemetry and forwarded logs to **Splunk**
- Simulated realistic attacks:
  - `nmap` port scanning
  - Reverse shell malware with `msfvenom`
  - Payload hosted using Python HTTP server
- Captured and analyzed all events using Splunk queries  
- Configured **internal network isolation** to safely execute and study malware behavior

📘 [Read the full blog post](https://medium.com/@vinuvarshith95/building-my-first-home-lab-b51d83145691)

### 🛠️ SOC Automation Lab
- Built a cloud-based SOC lab using **Wazuh**, **TheHive**, and **Shuffle** on DigitalOcean  
- Configured log collection from a Windows 11 endpoint using **Sysmon**  
- Automated alert triage with **Shuffle** and managed incidents via **TheHive**  
- Simulated attacks like **Mimikatz** and created **custom detection rules** in Wazuh 

📘 [Read the full write-up](https://medium.com/@vinuvarshith95/building-a-soc-automation-lab-phase-1-5f576b8b4497) | [Follow-up article](https://medium.com/@vinuvarshith95/building-a-soc-automation-lab-phase-2-7f3e46dc79f8)


### 🔍 Static Malware Analysis – XMoon.exe
- Performed **static analysis** on a Windows binary: `XMoon.exe`
- Verified file type using hex headers and DOS signatures (`MZ`)
- Extracted strings for IPs, C2 servers, APIs using:
  - `strings`, `FLOSS`, `XorSearch`, `BinText`
- Used **PEStudio** and **Exeinfo PE** to identify suspicious sections and packing indicators
- Checked hash reputation using **VirusTotal**

📘[Read the full blog post](https://medium.com/@vinuvarshith95/understanding-malware-a-journey-into-static-analysis-51238a5eed16)



## 🧠 More Projects

### 🏢 [Tata Group – Cybersecurity Simulation (Forage)](https://www.theforage.com/)
- Completed a virtual job simulation as an **IAM Developer**
- Conducted an **IAM Readiness Assessment** and documented risks in TechCorp's user lifecycle processes
- Proposed an **IAM Solution Design** with secure onboarding/offboarding and access control mechanisms
- Outlined a strategic **implementation plan** for deploying an IAM platform
- Gained experience in real-world IAM architecture design, threat modeling, and stakeholder reporting

### 🏦 [Commonwealth Bank – Cybersecurity Simulation (Forage)](https://www.theforage.com/)
- Simulated a cybersecurity analyst role at one of Australia’s largest banks
- Reviewed and responded to security incident reports
- Analyzed **phishing emails**, created a basic **SIEM alert triage**, and performed **threat analysis**
- Communicated technical risks and recommended actions to non-technical stakeholders
- Learned to assess **risk levels**, **identify false positives**, and generate **actionable insights**


## 🧰 Skills & Tools

- **Security**: Splunk, Wazuh, ELK, Zeek, Wireshark
- **Programming**: Python, C/C++, Bash
- **Virtualization**: VirtualBox, VMWare
- **OS**: Linux (Kali, Ubuntu), Windows 10/11
- **Tools**: PEStudio, Sysmon, Metasploit, FLOSS, VirusTotal, Git



## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vinuvarshith95&show_icons=true&theme=default" />
  <br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=vinuvarshith95" />
</p>



## 📫 Let’s Connect

- 💼 [LinkedIn – Vinu Varshith](https://www.linkedin.com/in/vinuvarshithalagappan/)
<!-- - 🧾 [Resume/CV](https://your-resume-link.com) -->
- ✉️ vinuvarshith95@gmail.com



> “Defenders think in lists. Attackers think in graphs. As long as this is true, attackers win.” – John Lambert

