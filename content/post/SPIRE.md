---
title: "SPIRE: Building antivirus using rust Part: 1"
categories: ["Spire"]
---

# Intro

The project can be found here on my [GitHub](https://github.com/Tokyo-09/spire)

![Spire Logo](/spire.jpeg)
Spire is being developed as a malware protection solution for both Linux and Windows, designed to protect end users from known malware and threats.

## Why's

* **Why this project exist?** -- Initially, I intended to develop my own firewall to deepen my understanding of the Rust programming language. While researching relevant materials, I frequently encountered publications from antivirus companies, which sparked significant interest. This inspired me to shift my focus and begin developing my own antivirus software. Given the limited number of resources and projects on this topic available on GitHub and across the internet, I decided to contribute to this field by creating my own solution.
* **Why choose rust?** -- As noted earlier, my initial goal was to gain a deeper understanding of the Rust programming language.
* **Why don't build everything with rust?** --Despite the advantages of the Rust programming language, developing full-fledged graphical user interface (GUI) applications with it currently presents certain challenges. Consequently, I chose Python for developing the user interface due to its simplicity and ease of use. For the server-side development, I opted for Go, as it is more convenient and better suited to my needs.

# Project plan

The project is still under active development, with continuous changes and updates. You can track my progress on my [GitHub Kanban board](https://github.com/users/Tokyo-09/projects/2), where all details are thoroughly documented and described, or refer to the list below.

## Features


**Client**

 * [ ] Send suspicious files to the server for further analysis
 * [ ] Log activities, collect data, and transmit it to the server
 * [ ] Automatically update the database from the server
 * [ ] Configuration management
...

**Core**
* [ ] Scan specified directories
* [ ] Scan using YARA rules
* [ ] Behavioral analysis
* [ ] Monitor mode
* [ ] TCP/IP filtering for malicious hosts/ports
* [ ] Scan each newly created file on disk for static Indicators of Compromise (IOCs)
* [ ] Scan each newly created file on disk for Import Address Table analysis
* [ ] Execute files in a sandbox upon detection of an executable launching from the kernel
...

Server

* [ ] Cloud-based file scanning
* [ ] Develop a basic website and API for the application
...


# Final thoughts

I have high expectations for this project, as the topic of antivirus protection greatly interests me, and I plan to continue its development. This blog is intended to document all stages of the development process and to describe the challenges I encounter or may encounter along the way.

If you are reading this and have any suggestions, please feel free to contact me via Twitter or GitHub!
