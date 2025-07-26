
## 📊 What You'll Find

- Inspection of HTTP GET/POST requests  
- DNS lookup traces  
- TCP 3-way handshake and teardown  
- Detection of anomalies or suspicious traffic

## ✍️ Why I Did This

Understanding how network protocols behave at the packet level is essential for system administrators, cybersecurity professionals, and backend engineers.  
This repository is part of my personal learning journey in networking fundamentals.

## ✅ Future Additions

- Add `.pcap` files with malware/suspicious activity (obfuscated if needed)  
- Use filters in `tshark` for automated reporting  
- Compare protocols over Wi-Fi vs Ethernet

## 📸 Sample Screenshot

_Add here a screenshot of a Wireshark packet list view or follow-stream of HTTP request if you want_

## 🏷️ Tags

`wireshark` `pcap` `network-analysis` `tcp` `dns` `http` `cybersecurity` `learning`

---

> Feel free to explore and use any of the analysis examples for your own learning or coursework.

<img width="643" height="447" alt="Screenshot 2025-07-26 152734" src="https://github.com/user-attachments/assets/765f07be-ffc0-45db-8ff8-9f5d9bde14cf" />


# Wireshark Traffic Analysis

This repository contains a summary of a packet capture analysis conducted with Wireshark. The goal was to observe key networking mechanisms such as TCP handshakes, encrypted HTTPS communication, file uploads, and ICMP behavior.

---

Wireshark Traffic Analysis Report
TCP handshake details and MSS value.

<img width="825" height="573" alt="image" src="https://github.com/user-attachments/assets/f816cbcd-62cb-4c6c-bcf9-eee23b25b5cb" />

TLS-encrypted HTTPS communication.

<img width="825" height="339" alt="image" src="https://github.com/user-attachments/assets/49ff88a2-f5cb-45d1-a351-2d95b23c9f63" />

Minimal TCP file upload stream.

<img width="825" height="522" alt="image" src="https://github.com/user-attachments/assets/e102e43d-cb42-402e-9ea7-621f3a183163" />

TLS Application Data packets.

<img width="825" height="419" alt="image" src="https://github.com/user-attachments/assets/12c01249-ec1b-4ce6-a189-d0003968aaa8" />

TCP segment structure with payload details.

<img width="825" height="450" alt="image" src="https://github.com/user-attachments/assets/40d89c09-7ebe-4a1f-8b92-e86700dbb99d" />

ICMP Echo Requests and Replies.

<img width="825" height="659" alt="image" src="https://github.com/user-attachments/assets/27358516-9fea-4167-ab0a-6fe1ffc18761" />

ICMP packet with MAC address metadata.

<img width="825" height="489" alt="image" src="https://github.com/user-attachments/assets/39e92536-a1df-43c7-9f3c-c0ddc9d9f3da" />





