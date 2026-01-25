# MD5 Hash Cracking Practice (John the Ripper)

This repository is created for **ethical hacking learning and practice** purposes.  
Here I practiced cracking **raw MD5 hashes** using **John the Ripper** with the **RockYou wordlist** and rules.

---


### Step 1: Run John the Ripper

```bash
john --format=raw-md5 --wordlist=/usr/share/wordlists/rockyou.txt --rules md5hash.txt

john --format=raw-md5 --show md5hash.txt

result:
?:123456
?:password
?:12345678
?:qwerty
?:1234
?:123
?:test
?:admin
?:user
?:12345
