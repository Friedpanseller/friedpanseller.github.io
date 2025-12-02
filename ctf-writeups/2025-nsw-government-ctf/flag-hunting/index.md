## 2025 NSW Government CTF
### Flag hunting

There's a flag here somewhere...where would I look?

The flag will be obvious once you've found it!

Author: Nosurf QA: b0unc3

Hint:  
It's somewhere on the CTF environment (nswgovctf.ctfd.io). No need to brute force anything, just hunt for all the usual locations that can give you good intel ;)

### Journey  

With the hint, the first thing I looked at was /robots.txt which had these entries:  
```
User-agent: *
Disallow: /admin
Disallow: /superadmin
```
The `/admin` page required an admin account to log in.  
The `/superadmin` page revealed the flag: `flag{sup3r_adm1n_1s_sup3r_dup3r}`.