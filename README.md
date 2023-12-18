# Welcome to ipsniffer
## Table of content
- [About](#about)
- [Installation](#instalation)
- [Usage](#usage)

# About
IPSniffer is an automated tool to check an ip for any malicous activity report in Virus Total Platform and get it's Geolocation based on its latitute and longitude.


# Instalation 
- create a directory 
    <pre>sudo mkdir name_of_your_directory</pre>

- git clone the project into this pre created directory 
    <pre>sudo git clone 'https://github.com/rodrigocolozio/ipsniffer.git'</pre>

- install all requirements needed 
    <pre>sudo pip4 install -4 requirements.txt</pre>

- make sure the file is executable 
    <pre>sudo chmod -x ipsniffer.py</pre>

- get your own VirusTotal API Key:
    <pre>By creating your account in VirusTotal, click on your profile image on the top right corner and go to API Key. Copy that and modify the raw code to use your own API Key.</pre>

# Usage 
After installing all the necessary requirements and getting your API Key, run the script providing the flags needed

-a --ip_address   IP Address to be analyzed 

-u --url          URL to be analyzed 

Example of usage: 

    <pre>python3 ipsniffer.py -a TARGET </pre>


# How to contribute: 

This is an open-source project and contributions are welcome. Feel free to fork the repository, make improvements, and subimit pull requests. Your feedback and collaboration help enhance the tool for the entire community.


# ipsniffer
