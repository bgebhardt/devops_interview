# Devops Interview

This repo contains some devops-related phone screen interview questions using unix tools.  The questions involve analyzing some files containing information (like logs files).

## Questions

**1. Checkout this repo**

**2. Expand rides_out.gz**

**3. How many files are there?**

**4. Each file represents 5 minutes of time.  How many minutes of down time is there?**

**5. Find all rides that are down**

Example of a ride that was down:
2017-07-15-07:05:01.csv:"Disneyland","Pinocchio's Daring Journey","0","Down","Sat Jul 15 2017 07:05:03 GMT-0700 (PDT)"

**6. How many rides were down?**

**7. We need to clean up a file.  Find all the places with double quotes ("") and replace them with single quotes ()")**

**8. Find all the unique ride names**

---
### Notes

answers file is encrypted.  Decrypt with: 
openssl des -d -in answers.md.enc -out answers.md

Encrypted with:
openssl des -in answers.md -out answers.md.enc

[How to encrypt files from the command line on the Apple Mac using OpenSSL | RAW Mac](http://www.rawinfopages.com/mac/content/how-encrypt-files-command-line-apple-mac-using-openssl)