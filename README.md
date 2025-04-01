# Super Python IP Stresser & IP Booter - Ultimate Network Stresser 🚀

**Made by https://nightmare-stresser.co 🌙**

## 🚀 Introduction

Say hello to **Super Python Stresser v3**—a powerhouse *Python IP Stresser* and *IP Booter* built for network enthusiasts and pros!

- 🎮 Packed with **14 game-specific floods**, **7 UDP**, **7 TCP**, and **6 HTTP** methods to push servers to their limits.
- 🔍 Features **CheckHost diagnostics** and **15 API-powered tools** for advanced network reconnaissance.
- ⚠️ **Warning:** For **educational and legal testing only**! Use on your own servers or with explicit permission. **Illegal use is strictly prohibited!** 🚨

---

## ✨ Features

### 🌟 Attack Methods:

#### 🎮 Game Methods (14 Total):
- **Minecraft Handshake:** Slams fake handshake packets (0x00).
- **Minecraft Login:** Floods with fake login attempts (0x02).
- **PUBG Packet:** UDP spam with PUBG identifiers.
- **PUBG Connect:** TCP connection overload.
- **Black Ops 6 Spam:** UDP packet flood for BO6.
- **Call of Duty Connect:** TCP slot filler.
- **CS:GO Query:** Overloads with Source query packets.
- **Rust Connect:** TCP connection spam.
- **ARK Spam:** UDP flood with ARK tags.
- **Fortnite Packet:** UDP flood with Fortnite flair.
- **Apex Legends Connect:** TCP connection barrage.
- **Valorant Spam:** UDP flood with Valorant tags.
- **GTA Online Connect:** TCP spam for GTA servers.
- **Roblox Query:** UDP flood with Roblox queries.

#### 🌊 Layer 4 UDP (7 Methods):
- 📦 **StdHex:** Floods with hex payloads (DEADBEEF).
- 📜 **Plain:** Simple UDP spam with "A" bytes.
- 🔄 **Bypass:** Randomized packet flood.
- 💥 **Burst:** High-intensity UDP bursts.
- 🌩️ **Storm:** Continuous flood with "STORM" tag.
- 🏃 **Rush:** Rapid UDP bursts.
- 💣 **Blast:** Randomized flood with "BLAST" tag.

#### ⚡ Layer 4 TCP (7 Methods):
- 🔗 **Bypass:** Randomized TCP payload flood.
- 🚪 **SYN:** Connection spam with SYN packets.
- 🔑 **ACK:** Floods ACK packets post-connection.
- 🌐 **Connect:** Opens/closes TCP connections.
- 🌊 **Wave:** Sustained TCP flood with "WAVE" payload.
- ⚡ **Surge:** Rapid TCP connection spam.
- 💥 **Crush:** Long-term TCP flood with "CRUSH" payload.

#### 🌐 Layer 7 HTTP (6 Methods):
- 📊 **Slowloris:** Keeps connections alive to drain resources.
- 🔎 **HTTP Spam:** Rapid GET requests to overload HTTP.
- 🔒 **HTTPS Bypass:** Proxy-powered HTTPS flood with UA rotation.
- 🔥 **HTTP Fury:** Rapid GET requests to /fury endpoint.
- ⚡ **HTTPS Strike:** HTTPS flood with custom UA.
- 📦 **HTTP Overload:** POST flood with random data.

### 🔍 CheckHost Tools:
- 📡 **Ping IP:** Basic ICMP ping check.
- 🌐 **HTTP Check:** Tests HTTP status via Check-Host.net.
- ℹ️ **Target Info:** Fetches IP location and connection stats.
- 🔗 **URL to IP:** Resolves URLs to IPs.

### 🛠️ API-Powered Tools (15 Total):
- 🌍 **IP Geolocation:** Detailed IP info (ip-api.com).
- 🔍 **Port Scanner:** Remote port scan (hackertarget.com).
- 📜 **WHOIS Lookup:** Domain details (whois.vu).
- 🌐 **DNS Resolver:** DNS records (Cloudflare 1.1.1.1).
- 📏 **Bandwidth Test:** Bandwidth estimate (hackertarget.com).
- 🔒 **SSL/TLS Checker:** SSL/TLS security analysis (ssllabs.com).
- 🗺️ **Traceroute:** Network path mapping (hackertarget.com).
- 🌐 **Subdomain Finder:** Lists subdomains (hackertarget.com).
- 📊 **IP Reputation:** Abuse reports (abuseipdb.com, needs API key).
- 📸 **Website Screenshot:** Site capture (screenshotmachine.com, needs API key).
- 🔐 **DNS Leak Test:** Checks for DNS leaks (bash.ws).
- 📋 **HTTP Headers:** Analyzes response headers (hackertarget.com).
- ⚠️ **IP Blacklist:** Blacklist status (blacklistchecker.com, needs API key).
- ⏱️ **Network Latency:** Measures ping latency (hackertarget.com).
- 🛡️ **Vulnerability Scanner:** Basic vuln check (hackertarget.com).

### 🎨 Customization:
- 🎯 **IP & Port:** Target any server (e.g., 25565 for Minecraft).
- ⏱️ **Duration:** Set attack length in seconds.
- 📏 **Packet Size:** 1-65500 bytes for UDP/TCP methods.

### 🖥️ Cool Vibes:
- 🎨 ASCII art intro: `Super Python Stresser V3 - Made by https://nightmare-stresser.co`.
- 🌈 **Colors:** Cyan (start), Green (done), Red (errors).
- 📊 **Tracks packets/connections/requests** post-attack.
- 🏷️ Window title: `Super Python Stresser V3 By nightmare-stresser.co`.

---

## 🛠️ Installation

### 📋 Requirements:
- 🐍 **Python 3.x** (Pre-installed on Ubuntu, or download from [python.org](https://www.python.org/))
- 💻 **A terminal** (Bash on Ubuntu, Command Prompt/PowerShell on Windows)

### 🚀 Steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/super-python-stresser-v3.git
   cd super-python-stresser-v3


   Replace yourusername with your GitHub username. 😉

Install Required Libraries:
bash

Collapse

Wrap

Copy
pip3 install colorama requests
🌈 colorama: Adds colorful console output.
🌐 requests: Powers HTTP attacks and API calls.
Run the Tool:
bash

Collapse

Wrap

Copy
python3 super_python_stresser_v3.py
🪟 Windows? Try python if python3 fails.
🔑 TCP methods may need root/admin privileges for max impact.
🎮 Usage
▶️ Launch It:
🚀 Window title sets to Super Python Stresser V3 By nightmare-stresser.co.
🖥️ You’ll see:
text

Collapse

Wrap

Copy
******************************************
*      Super Python Stresser V3          *
*    Made by https://nightmare-stresser.co *
*      Advanced Network Stress Tool      *
******************************************
Welcome, TestUser!
Current Date & Time: 2025-03-31 15:45:22
🎯 Pick Your Category:
🎮 1 for Game Methods, 🌊 2 for UDP, ⚡ 3 for TCP, 🌐 4 for HTTP, 🔍 5 for CheckHost, 🛠️ 6 for Tools, 7 for Credits.
Enter IP, port, duration, and (where applicable) packet size.
Use 0 to go back to the main menu.
Example: Fortnite Packet Flood
text

Collapse

Wrap

Copy
Select category (1-7): 1
Game Methods:
  1. Minecraft Handshake Flood
  ...
  10. Fortnite Packet Flood
  0. Back
Select method (0-14): 10
Enter target IP: 192.168.1.100
Enter port (1-65535): 12345
Enter duration (seconds): 5
Starting Fortnite Packet Flood on 192.168.1.100:12345 for 5 seconds...
Completed! Sent 400 packets.
Example: Traceroute
text

Collapse

Wrap

Copy
Select category (1-7): 6
Tools:
  1. IP Geolocation Lookup
  ...
  7. Traceroute
  0. Back
Select tool (0-15): 7
Enter IP: 8.8.8.8
Performing Traceroute to 8.8.8.8...
Traceroute Results:
traceroute to 8.8.8.8 (8.8.8.8), 30 hops max, 60 byte packets
 1  192.168.1.1  2.345 ms
 2  10.0.0.1  5.678 ms
 3  8.8.8.8  10.123 ms
🧠 How It Works
Game Methods: Targets specific game protocols (e.g., Minecraft handshakes, CS:GO queries).
Layer 4: Overwhelms bandwidth or connections with UDP/TCP floods.
Layer 7: Drains server resources via HTTP/HTTPS requests.
CheckHost: Leverages Check-Host.net for diagnostics.
Tools: Uses free APIs for reconnaissance and testing.
📈 Counts packets, connections, or requests after every run!

🌟 Learn More
Curious about the top 5 free IP Stresser tools in 2025? Check out this guide by Nightmare Stresser:

Top 5 Best Free IP Stresser Tools in 2025

🙌 Credits
🌙 Made by https://nightmare-stresser.co!
🔥 Crafted by the network pros at https://nightmare-stresser.co.
🚀 Your elite hub for server stress-testing and diagnostics!

📜 License
⚖️ For educational and legal testing only.
🚫 No formal license—use responsibly!
Disclaimer: This Python IP Stresser is for educational and ethical testing only. Use it legally on systems you own or have permission to test. Misuse is your responsibility!
