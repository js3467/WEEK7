# WEEK7
# Project 7 - WordPress Pentesting

Time spent: **17** hours spent in total - most of time spent due to errors
								setting up wordpress 4.2

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (8111) Vulnerability Name or ID
  - [ ] Summary: XXS vulnerability on mouse over. 
    - Vulnerability types: XXS
    - Tested in version: 4.2
    - Fixed in version: 4.2.3
  - [ ] GIF Walkthrough: 
	1. https://imgur.com/noqHvFk
	2. https://imgur.com/n8Mg6OS
  - [ ] Steps to recreate: 
	1. as user post “<a href="[caption code=">]</a><a title=" onmouseover=alert('test')  ">link</a>”
		as a comment
	2. Admin approves comment
	3. Proof of concept - https://youtu.be/OCqQZJZ1Ie4
    - [ ] Affected source code:
    - [Link 1](GitHub link not posted on the wp vuln)


2. (Author XXS) Vulnerability Name or ID
  - [ ] Summary: When creating a new page you run an XXS attack in the header
    - Vulnerability types:XXS
    - Tested in version:4.2
    - Fixed in version: 4.6.1
  - [ ] GIF Walkthrough: https://imgur.com/UGvVANV
  - [ ] Steps to recreate: <IMG SRC=“#” ONERROR=“alert(’xxs’)”/>



3. (User Enumeration) Vulnerability Name or ID
  - [ ] Summary: The website allows for wordlists to be run.
    - Vulnerability types: Enumeration
    - Tested in version: 4.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
	1. https://imgur.com/1jNpbet
	2. https://imgur.com/VtPyMUI
  - [ ] Steps to recreate: use a word list and run the command in the gif and 


## Resources

- wpvulndb.com/exploitnumber
- https://youtu.be/OCqQZJZ1Ie4
- 

GIFs created with gifox.

## Notes

This lab caused me struggles every step of the way. I spent hours trying to reconfigure wordpress to get it to run any version that was not the most updated one. That is why this is late. Even after I had it running I ran into smaller issues. 
