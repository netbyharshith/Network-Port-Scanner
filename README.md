** Network-Port-Scanner**

**Project Summary:**
This project implements a network port scanner using Python. It scans a target host for open ports in a given range and reports them. It is useful for basic vulnerability assessments or network troubleshooting.

**Obejectives:**
* Scan a specific host for open TCP ports.

* Provide real-time feedback on port status.

* Handle common exceptions and delays.

* Offer an educational understanding of socket programming and network security.

**Technologies Used:**
* Python 3

* Socket Programming

* Jupyter Notebook (.ipynb interface)

* Time module

* Threading

**Features:**
* Accepts IP address or hostname as input.

* Scans a range of ports (default: 1–1024).

* Uses TCP to test connectivity to each port.

* Prints open ports and optionally saves to a log file.

**How to Run:**
* Install Python 3 (if not installed)
sudo apt install python3

* Open the Notebook:
jupyter notebook port_scanner.py.ipynb

* Run all cells, and provide a target when prompted.

* Example usage (in script version):
python3 port_scanner.py <hostname_or_ip>

 **Example Output:**
 Scanning host: 192.168.1.1
Port 22: OPEN (SSH)
Port 80: OPEN (HTTP)
Port 443: OPEN (HTTPS)

**Use Cases:**
* Penetration testing (basic).

* Home network security scanning.

* Educational purposes (network fundamentals).

* Server port availability check.

**Future Enhancements:**
* Add multi-threading to speed up scanning.

* Include UDP port scanning.

* Add GUI using Tkinter or PyQt.

* Export results to CSV or JSON.

* Add Nmap API integration.
 
 **Conclusion:**
 This port scanner project demonstrates practical applications of Python in network programming and security. It provides a foundation for more advanced tools and promotes learning through hands-on development.
