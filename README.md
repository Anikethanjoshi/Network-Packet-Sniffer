# Network Packet Sniffer Web App

This is a web-based network packet sniffer built using **Flask**, **Scapy**, **HTML**, and **JavaScript**. It captures live packets from a specified network interface, displays real-time packet summaries, and allows downloading the captured data.

##  Features

-  Web interface to start and stop live packet capture
-  Displays packet information: source IP, destination IP, protocol, ports, payload, and packet length
-  Clickable list to view full packet details
-  Download captured packets as a `.txt` file
-  Easy selection of network interfaces (Wi-Fi, Ethernet, Bluetooth)
-  Auto-refreshes captured packets every second

##  Technologies Used

- **Python**  
- **Flask** (web framework)  
- **Scapy** (packet sniffing and dissection)  
- **HTML/CSS/JavaScript** (frontend)


## ▶️ How to Run

### 1. Install Dependencies

Make sure you have Python and pip installed, then run:

```bash
pip install flask scapy
```
> ⚠️ Run the app with administrator/root privileges to allow packet sniffing.

### 2. Start the Application

```bash
python app.py
```

### 3. Open in Browser

Go to [http://127.0.0.1:5000](http://127.0.0.1:5000) and use the web interface to:
- Select a network interface (e.g., Wi-Fi, eth0)
- Start and stop packet capture
- View live packets and their details
- Download the captured log

---

##  Current Functionality

- Captures IP-based packets using Scapy
- Filters and displays key information
- Real-time packet list with clickable details
- Data export to text file

---

##  Possible Enhancements

- Add protocol filter (TCP, UDP, ICMP)
- Graphical packet statistics (using Chart.js or D3.js)
- Timestamp for each packet
- Search or filter by IP, port, or protocol
- Export data as `.csv` or `.pcap` for Wireshark

##  Disclaimer

This tool is intended **for educational and research purposes only**. Do not use it on networks you don’t own or have explicit permission to monitor.

## Contact

For questions or suggestions, feel free to reach out.
