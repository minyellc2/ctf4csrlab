# What is CTF?
**Capture The Flag (CTF)** is a cybersecurity competition where players solve technical puzzles to find hidden text strings called **flags** (e.g., `UCSYCTF{example_text}`).

---

# Types of CTF

* **Jeopardy-style:** A team or individual competition featuring a board of static challenges grouped by category.
* **Attack-Defense:** Teams defend their own vulnerable servers while hacking rival teams' servers to steal flags.
* **King of the Hill (Mixed):** Similar to Jeopardy-style, but players must hack a target system to capture the flag, and then patch it to defend it from other teams.

# Categories & Core Tools
## 1. Web

### Recon
- Wappalyzer
- GoogleDork
- Gobuster
- ffuf
- dnsenum
- WayBackMachine
- Aws Buckets
  
### Exploit
 - Burpsuite
 - Curl
 - Python
 - CVE , Bug Reports
 - [Exploit-DB](https://www.exploit-db.com/)

---

## 2. OSINT -> Open Source Intelligence

### Image
- Exiftool
- Google Image Search Engine

### Web 
- whois
- nslookup
- Google Dork
- [WayBackMachine](https://web.archive.org/)

### Accounts
- sherlock
- [whatsmyname.app](https://whatsmyname.app/)
- [EPIEOS](https://epieos.com/) for email


## 3. Steganography

### Image
- exiftool
- strings
- xxd
- hexedit | hexeditor
- steghide
- stegcracker
- stegsolve
- zsteg
- foremost
- binwalk
- openstego
- GIMP
- [Aperi'Solve](https://aperisolve.com/)
- python library

### Audio & Video
- Audacity
- Sonic Visualizer
- [MorseCode](https://morsecode.world/international/decoder/audio-decoder-adaptive.html)
- DeepSound
- Videosteg

### txt files
- xxd ( space and tab -> 0 & 1)
- whitespace cipher
- stegsnow

## 4. Forensics
### Disk Forensics
- Autopsy
- FTK Imager
- ALEAPP & iLEAPP

### Memory Forensics
- Strings
- Volatility

### Network Forensics
- Wireshark
- tcpdump , tshark ( cli tools )
- Network Miner

## 5. Reverse Engineering (RE) & Binary Exploitation (Pwn)



### Static Analysis (Reverse Engineering)

- file / ldd

- strings / xxd

- Ghidra

- IDA Pro / IDA Free

- Cutter (Radare2 GUI)

- Binary Ninja



### Dynamic Analysis & Debugging

- gdb (with GEF or pwndbg extension)

- x64dbg

- strace / ltrace



### Exploitation & Scripting (Pwn)

- Pwntools (Python library)

- checksec (Mitigation checker: ASLR, NX, Canary)

- ROPgadget / ropper (Return-Oriented Programming chains)

- One_gadget



---



## 6. Cryptography



### Classic & Encoding ciphers

- [CyberChef](https://gchq.github.io/CyberChef/)

- [dCode.fr](https://www.dcode.fr/)

- Caesars / Vigenère / ROT13

- Base32 / Base64 / Base85



### Modern Symmetric & Asymmetric Crypto

- SageMath (Advanced mathematics framework)

- Python (PyCryptodome library)

- RsaCtfTool (Automated RSA attacks)

- John the Ripper / Hashcat (Hash cracking)



---



## 7. Miscellaneous (Misc)



### Jailbreaking & Esoteric Languages

- PyJail (Python sandbox escapes)

- Brainfuck / Esolang decoders



### Automation & Logic

- Python (socket, requests libraries)

- Netcat (`nc`)
