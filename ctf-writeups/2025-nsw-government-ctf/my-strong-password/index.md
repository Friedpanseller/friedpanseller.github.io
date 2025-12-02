## 2025 NSW Government CTF
### My Strong Password

So I have to have at least three of the following to make a strong password?: An uppercase, lowercase, numbers and special characters.

Well, here's the md5 of my strong password, it'll be hacker proof!!

2c103f2c4ed1e59c0b4e2e01821770fa

Wrap the password within flag{...}, e.g. flag{password}

Author: Nosurf QA: b0unc3

### Journey  

There were two ways to approach this. Generate a wordlist of uppercase, lowercase, numbers, and special characters, and try to match the MD5 hash of each to the one provided.  

The other way is to check if this hash has been computed already. [CrackStation](https://crackstation.net/) hosts a table of pre-computed hashes.  

Entering the hash at Crack Station reveals the password `	Password123!`