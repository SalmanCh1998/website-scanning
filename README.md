# website-scanning
Network Information Tool 

Usage
Install Dependencies:
Ensure you have the necessary Python libraries installed:

sh
Copy code
pip install scapy
Run the Application:
Since Scapy requires raw socket permissions, the script should be run with elevated privileges.

On Linux:

sh
Copy code
sudo python3 network_info_tool.py
On Windows:
Run the script as an administrator by opening a Command Prompt with administrative privileges and executing:

sh
Copy code
python network_info_tool.py
Enter URL: In the GUI window, enter the URL of the website or server you want to check.

Get Network Info: Click the "Get Network Info" button to see the IP address and reachability status of the host.

Example
Input: www.example.com
Output:
yaml
Copy code
IP Address: 93.184.216.34
Host Reachable: Yes
