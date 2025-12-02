## 2025 NSW Government CTF
### Salads

We caught this string of characters being sent out to a Command and Control (C2) server. It appears to be a very basic cipher. Can you work out what it is?

jxyisxqbbudwucqtucuxkdwho

Wrap the plaintext within flag{...}, e.g. flag{plaintext}

Author: Nosurf QA: b0unc3

### Journey  

The most basic cipher is a caesar cipher. There are two websites we can use.  

[rot13.com](https://rot13.com/) is a simple to use one that is easy to work with.  

I like to use [DCode](https://www.dcode.fr/) which has a caesar-cipher decoder that tells you which shift number is used instead of navigating through all 26 and checking the results manually.  

DCode revealed that a rotation of 10/16 produced `thischallengemademehungry` which is the flag.