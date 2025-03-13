🛡️ IP Filter Project

This project is a simple yet efficient Python script designed to manage IP filtering. It allows me to remove specific IP addresses from an allow_list.txt file. This is particularly useful for maintaining security, automating access control, and ensuring that restricted or blacklisted IPs are not included in the allowed list. The script reads an existing list of IP addresses, filters out the unwanted ones, and updates the file accordingly.

🛠️ Installation & Setup

Next, I check if Python is installed:

python --version

If Python isn’t installed, I download and install it from python.org. Then, I run the script:

python update_ip_list.py

💻 How I Use It

This script reads allow_list.txt, stores IP addresses in a list, filters out IP addresses present in remove_list, writes the cleaned list back to allow_list.txt, and prints the updated list to the console.

📌 Example

If allow_list.txt originally contains:

192.168.25.60 192.168.140.81 192.168.203.198 192.168.1.1

When I run:

update_file('allow_list.txt', ["192.168.25.60", "192.168.140.81", "192.168.203.198"])

It updates allow_list.txt to:

192.168.1.1

📝 How the Code Works

![Description](https://i.imgur.com/HpQNI9l.png)





🔥 Features

Efficiently removes unwanted IPs

Simple usage – I just edit allow_list.txt and run the script

Fast execution using optimized list filtering



