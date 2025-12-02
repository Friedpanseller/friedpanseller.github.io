## 2025 NSW Government CTF
### Where is this?

Open Source Intelligence (OSINT) challenges come in a few flavours. One type of OSINT challenge is trying to work out exactly where a photo was taken.

Can you find this location based on what you see in the photos?

Wrap the latitude and longitude within flag{...}, to the nearest three decimals and without any spaces. For example, flag{-30.123,148.123}

Author: Nosurf QA: b0unc3

[⬇️ whereisthis.jpg](whereisthis.jpg)

### Journey  

I uploaded the image to [Google Reverse Image Search](https://images.google.com) and was informed the building is 4 Parramatta Square, Sydney, Australia. In [Google Maps](https://maps.google.com) I entered that location, and got the coordinates `-33.817,151.004`.  

The challenge said the flag was incorrect, so I thought I must have been a few metres off the actual location. Playing around with the last decimal place a bit reveals the flag to be `-33.816,151.005`.