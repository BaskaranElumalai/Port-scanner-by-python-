# Port-scanner-by-python-

🔍 Port Scanner

This project is a simple Python-based port scanner that allows you to scan a target IP address for open TCP ports within a specified range.

📁 File

port_scanner.py: The main script for scanning ports using Python's socket library.



---

🚀 Features

Scans a given IP address for open ports.

Specify the start and end port range.

Uses socket with timeout handling for responsiveness.

Returns a list of open ports.



---

🛠️ Requirements

Python 3.x


No external libraries are required; only the built-in socket and typing modules are used.


---

🧪 Usage

# Step 1: Run the script from Python
python port_scanner.py

Or, if you plan to import the function in another script:

from port_scanner import scan_ports

target_ip = '192.168.1.1'
open_ports = scan_ports(target_ip, 20, 1024)

print(f"Open ports on {target_ip}: {open_ports}")


---

📝 Function Documentation

scan_ports(target: str, start_port: int, end_port: int) -> List[int]

Scans a range of ports on a target IP address.

Parameters:

target: Target IP address (e.g., '192.168.1.1')

start_port: Start of port range (e.g., 20)

end_port: End of port range (e.g., 1024)


Returns:

List of open ports found within the specified range.



---

⚠️ Disclaimer

This tool is intended only for ethical and educational purposes. Do not scan IP addresses or networks without permission.
