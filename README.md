# Boogeyman 2 Investigation - Capstone Project

## Overview
Investigation of the Boogeyman 2 compromise at Quick Logistics LLC: an HR user opened a malicious resume (phishing + macro). Using static macro analysis and Volatility 3, I reconstructed the attack chain and identified execution, persistence, and C2 activity.

This project was made using the website [TryHackMe](https://tryhackme.com/).

## Scope
Phishing email + malicious doc, memory image analysis, IOC collection.

## Key Learnings
- Reconstructed phishing attack and malicious macro execution.
- Extracted memory artifacts and traced persistence mechanisms.
- Identified network indicators and C2 activity.