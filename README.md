# MD5 Hash Cracking Practice (John the Ripper)

This repository is created for **ethical hacking learning and practice** purposes.  
Here I practiced cracking **raw MD5 hashes** using **John the Ripper** with the **RockYou wordlist** and rules.

---

## Clone the Repository

```bash
git clone https://github.com/samrat-xyz/md5hash-cracking.git
cd md5hash-cracking
john --format=raw-md5 --wordlist=/usr/share/wordlists/rockyou.txt --rules md5hash.txt
john --format=raw-md5 --show md5hash.txt
