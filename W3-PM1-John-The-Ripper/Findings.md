# 🔍 Findings – John the Ripper (W3-PM1)

## 1. Objective

The objective of this practical task was to understand PDF password hash extraction and perform dictionary-based password cracking using John the Ripper.

## 2. Lab Environment

- Operating System: Kali Linux
- Password Cracking Tool: John the Ripper
- Wordlist: RockYou
- Target: Authorized encrypted PDF file

## 3. Methodology

1. Selected an encrypted PDF file for the authorized exercise.
2. Extracted the PDF password hash using an online hash extraction tool.
3. Saved the extracted hash in a text file named `pdf3.txt`.
4. Used the RockYou wordlist to perform a dictionary attack.
5. Executed John the Ripper in the Kali Linux terminal.
6. Analyzed the cracking output.

## 4. Command Executed

```bash
john --wordlist=/usr/share/wordlists/rockyou.txt pdf3.txt
```

## 5. Observations

- John the Ripper successfully loaded the PDF hash.
- The dictionary attack was executed using the RockYou wordlist.
- A matching password candidate was identified.
- The cracking session completed successfully.

## 6. Conclusion

Successfully completed the W3-PM1 practical task and gained hands-on experience with PDF hash extraction, wordlist-based password auditing, and John the Ripper.

## 7. Evidence

Practical screenshots are available in the `Screenshots` directory.
