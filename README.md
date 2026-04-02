# 🔍 Network Port Scanner (Python GUI)

## 📌 Project Overview
This project is a **multi-threaded network port scanner** with a **graphical user interface (GUI)** built using Python and Tkinter.

The tool allows users to scan a target system (IP or hostname) to identify **open ports and running services**, helping in basic network reconnaissance and security analysis.

---

## 🎯 Features
- Scan any target (IP address or hostname)
- Custom port range selection (0–65535)
- Multi-threaded scanning for faster performance
- Real-time progress tracking
- Displays open ports with associated services
- Save scan results to a file
- User-friendly GUI interface

---

## 🛠️ Technologies Used
- **Python**
- **Socket Programming**
- **Multithreading (threading module)**
- **Tkinter (GUI)**
- **Queue (for thread communication)**

---

## ⚙️ How It Works

1. User enters:
   - Target (IP/Hostname)
   - Start Port
   - End Port  

2. The scanner:
   - Resolves the target IP
   - Creates multiple threads
   - Scans ports using TCP connections

3. For each port:
   - If connection succeeds → Port is OPEN
   - Service is identified using common port mapping

4. Results are displayed in real-time in the GUI

---


---

## 🖥️ GUI Overview
- Input target and port range  
- Click **Start Scan**  
- View results in real-time  
- Save results to a file  

---

## ⚠️ Disclaimer
This tool is developed for **educational and ethical purposes only**.

Do NOT use this scanner on networks or systems without proper authorization.

---

## 📚 Learning Outcomes
- Understanding of network ports and services  
- Hands-on experience with socket programming  
- Implementation of multithreading in Python  
- GUI development using Tkinter  
- Basics of network reconnaissance  

---

## 🔮 Future Improvements
- Add service version detection  
- Add UDP scanning support  
- Export results in CSV/JSON format  
- Improve GUI design and user experience  
- Add vulnerability detection features  

---

## 🤝 Connect With Me
**Name:** Mahek Jariwala  
**Field:** Cybersecurity  

Feel free to connect and discuss cybersecurity projects!
