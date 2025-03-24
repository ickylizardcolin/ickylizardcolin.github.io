---
layout: post
title:  "Pwning library cards"
tags: hacking
---
# Pwning library cards
## Disclaimer
{% include pentest-disclaimer.html %}
## Process
### Why
I lost my library card but had seomeone else's that belonged to the same library. 
### Physical
I scanned the barcode using [Binary Eye (fdroid)](https://f-droid.org/en/packages/de.markusfisch.android.binaryeye/ "Install me!") (best scanner.) It was a 16-character CODABAR barcode mesasuring just under 2in/5cm wide and 1/4in/1cm long.
### Formatting
The First and last bytes were "A", with 14 ASCII-encoded numbers between them. I replicated the bar code, printed it off, and got into my account.
