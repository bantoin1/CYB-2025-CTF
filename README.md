# CYB-2025-CTF
Here’s an updated version of your CTF README incorporating the Wireshark `.pcap` file for extra intrigue:

---

# Welcome to the "Login Logic Challenge" CTF!

## Challenge Overview
Your mission is to solve a multi-layered challenge that involves analyzing network traffic, identifying a website, and unraveling the login logic. This task will test your skills in packet analysis, web exploration, and JavaScript decryption.

## The Story
During a digital forensics investigation, you stumbled upon a mysterious `.pcap` file captured using Wireshark. Hidden within the captured traffic is a reference to a login page on a website. After finding the page, you'll encounter a login system with encrypted data. Your goal is to discover the website, bypass the login system, and decrypt the hidden flag!

Can you solve the puzzle and retrieve the flag?

## Objectives
1. Analyze the `.pcap` file to identify the website hosting the login page.
2. Access the login page and examine its JavaScript logic.
3. Reverse the encryption to reveal the flag.

## Rules
1. Do not use brute force or automated tools to guess credentials.
2. Stick to analyzing the provided artifacts and logic.
3. Have fun and learn responsibly!

## Instructions
1. Download the challenge files:
    - `capture.pcap` (The Wireshark capture file)
    - `index.html` (The login page HTML)
    - `encryptDecrypt.js` (Contains the JavaScript logic and encrypted flag)
    - `styles.css` (Optional: Adds a visual touch to the login page)

2. Open the `.pcap` file in Wireshark and analyze it to identify the website mentioned in the captured traffic.

3. Access the identified website and inspect the `index.html` and `encryptDecrypt.js` files.

4. Examine the JavaScript code. Pay close attention to:
    - The encrypted message
    - The secret key
    - The username and password validation

5. Reverse the encryption logic or find the correct credentials to decrypt the flag.

6. Submit the flag in the format: `flag{your-answer}`.

## Flag Example
Once you solve the challenge, the decrypted flag will look like:
```
flag{good-job-this-was-easy}
```

## Tools and Techniques
You may use:
- Wireshark to analyze network traffic.
- A browser's developer tools to inspect the website.
- JavaScript debugging tools.
- A text editor to analyze the logic in the files.

## Hints
- Look for HTTP or HTTPS traffic in the `.pcap` file to uncover the website address.
- Examine how the `CryptoJS` library handles encryption and decryption in `encryptDecrypt.js`.
- Don't overlook the username and password validation logic.

---

This updated version adds a forensic twist by incorporating the `.pcap` file into the narrative. It should make the challenge more engaging! Let me know if you'd like further changes or additions.
