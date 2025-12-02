## 2025 NSW Government CTF
### Funny looking code

I've found some funny looking code when unpacking some malware, what could it mean?

ZmxhZ3thMTFfeTB1X2JhczNfYXIzX2JlbDBuZ190MF91c30=

Author: Nosurf QA: b0unc3

### Journey  

This string seems like base64 encoded as it containes alphanumeric characters with a trailing equal sign.  

In CyberChef, we can convert From Base64 and it reveals the flag `flag{a11_y0u_bas3_ar3_bel0ng_t0_us}`.  

Alternatively, you can pipe the string in Kali into the base64 decoder `echo "ZmxhZ3thMTFfeTB1X2JhczNfYXIzX2JlbDBuZ190MF91c30=" | base64 -d`.