# Week-3-cyber-security
Week 3 – Password Cracking Lab

Project Overview

This project explores password recovery techniques using two different approaches as part of my cybersecurity practical work.

The practical involved working with a password-protected PDF, extracting password hashes, using John the Ripper and testing an online password-cracking tool.

Objectives

Understand how password-protected PDF files work.

Extract a PDF password hash.

Use John the Ripper to attempt password recovery.

Explore the Networkwalks Hash Calculator.

Test password recovery using the Networkwalks Password Cracker.

Understand the importance of wordlists in password-cracking attempts.

Tools and Technologies

Kali Linux – Linux environment used for the practical.

John the Ripper – Password-cracking tool.

Johnny – Graphical interface for John the Ripper.

RockYou wordlist – Common-password wordlist.

Networkwalks Hash Calculator – Used to generate and inspect hashes.

Networkwalks Password Cracker – Used to test password recovery.

Firefox – Used to access online tools.

Practical Module 1 – John the Ripper

Steps Performed

Opened Kali Linux.

Checked that John the Ripper was installed.

Extracted the RockYou wordlist.

Located the provided password-protected PDF.

Extracted the PDF hash and saved it into a text file.

Opened Johnny and loaded the hash file.

Started the password-cracking process.

Observed the cracking result in Johnny.

Result

Johnny displayed a successful result, showing that the hash had been cracked.

Evidence: Screenshots of the terminal setup, extracted hash, Johnny interface and cracking result.

Practical Module 2 – Networkwalks Tools

Steps Performed

Opened the Networkwalks Hash Calculator.

Uploaded the provided PDF file.

Viewed the generated hash information.

Selected the PDF hash section.

Copied the extracted PDF hash.

Opened the Networkwalks Password Cracker.

Submitted the hash and tested the available password list.

The online tool completed 100 attempts but did not find a match.

Checked the RockYou wordlist for password1.

Independently verified the password by successfully opening the PDF.

Result

The online Password Cracker did not find a match within its 100 attempts. However, the password password1 was independently verified by successfully opening the protected PDF.

Challenges Faced

Johnny was initially missing, so I updated Kali's package list and installed it.

I needed to extract the RockYou wordlist before using it.

Extracting the correct PDF hash required selecting the correct hash format.

The Networkwalks Password Cracker did not find a match within its limited 100 attempts.

I had to verify the password independently by opening the PDF.

These challenges helped me understand the importance of selecting the correct hash format, using suitable wordlists and checking results carefully.

Key Learning Outcomes

Gained practical experience using Kali Linux.

Learned how to extract password hashes from PDF files.

Practised using John the Ripper and Johnny.

Understood the role of wordlists in password recovery.

Learned that a failed cracking attempt does not necessarily mean the password is unrecoverable.

Improved troubleshooting and problem-solving skills.

Conclusion

This practical introduced me to password-cracking techniques and tools used in cybersecurity. I gained hands-on experience with John the Ripper, Johnny and Networkwalks tools while learning how hash extraction and wordlists contribute to password recovery.
