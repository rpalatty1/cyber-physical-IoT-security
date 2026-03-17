# Cyber-Physical Systems & IoT Security Labs

**Module:** COMP3217 – Security of Cyber Physical Systems  

## Overview
Security analysis of embedded systems, contactless cards, IoT devices, and wireless communication protocols, including practical exploitation of real-world vulnerabilities.
Demonstrated practical attack techniques and analysis skills.

## Tools & Technologies
- ChipWhisperer (side-channel analysis)  
- Software-Defined Radio (PlutoSDR, LimeSDR)  
- Universal Radio Hacker, gqrx  
- MIFARE Classic/NFC tools (mfoc, nfc-tools)  
- Kali Linux, Wireshark, gr-gsm  

## Key Labs & Work

### Lab 1: Contactless Card Security
- Analysed NFC card structure and memory layout  
- Cracked MIFARE Classic keys using offline attacks  
- Read, modified, and cloned card data  
- Explored access control bits and "magic card" behaviour  

### Lab 2: Side-Channel Attacks 
- Captured and analysed power traces from embedded devices  
- Performed timing and power analysis to brute-force passwords  
- Executed Correlation Power Analysis (CPA) to recover AES keys  
- Investigated hardware-level cryptographic weaknesses  

### Lab 3: Security of an IoT Device
- Captured and decoded wireless signals from IoT devices  
- Replayed RF signals to trigger device actions (replay attack)  
- Analysed modulation schemes and signal structure  
- Explored fuzzing approaches for wireless protocols  

### Lab 4: Security of GSM Communication
- Sniffed and analysed GSM traffic using SDR and Wireshark  
- Extracted network parameters (MCC, MNC, ARFCN, TMSI)  
- Decoded SMS messages from captured traffic  
- Investigated weaknesses in legacy mobile communication protocols  

## Security Concepts
- Side-channel attacks (CPA, power analysis)  
- Replay attacks & RF exploitation  
- Weak authentication (NFC cloning)  
- Network protocol analysis (GSM, IoT comms)  
- Cryptographic weaknesses in embedded systems  

## Skills Demonstrated
- Embedded & hardware security  
- Wireless/RF signal analysis  
- Cryptographic attack techniques  
- Protocol analysis & packet inspection  

## Deliverables
- Lab reports and technical analysis  
- Power trace captures & SDR recordings  
- NFC card dumps and attack results  
