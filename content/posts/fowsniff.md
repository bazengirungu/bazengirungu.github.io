---
title: "Fowsniff"
draft: false
date: 2025-08-22 01:09:33 +0300
description: A beginner-friendly Boot2Root machine from THM.
categories: [ "Hash Cracking", "OSINT", "Google Dorking", "THM", "TryHackMe", "NMAP", "POP3", "IMAP", "SSH"]
tags: ["THM", "TryHackMe", "NMAP", "POP3", "IMAP", "SSH", "Hash Cracking", "Hydra", "LinPEAS", "easy", "boot2root", "B2R", "OSINT", "Google Dorking", "Privilege Escalation", "Reverse Shell", "Email Enumeration"]
featureimage: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTg1cKoR6tgXuXKI148RqMfXDvddGW_fAkhfw&s"
---

# Fowsniff CTF - Complete Beginner's Walkthrough

## What is This?


**What you'll learn:**


## Prerequisites


## Lab Setup
### Starting the Machine


## Phase 1: Reconnaissance & Enumeration

### What is Reconnaissance?

### Step 1: Network Scanning with Nmap



**Command breakdown:**


**Output:**


**What we discovered:**


### Step 2: Web Application Investigation






**Command breakdown:**


## Phase 2: OSINT (Open Source Intelligence)



### Step 3: Google Dorking Discovery





### Step 4: Analyzing the Password Dump



**Our discovered data:**


### Step 5: Cracking Password Hashes



**Our cracked credentials:**



## Phase 3: Email Protocol Exploitation


### Step 6: Connecting to the POP3 Service



**Important Email Content:**



**Key Discovery:**


## Phase 4: SSH Access



### Step 7: Finding Who Still Uses the Default Password



**Command breakdown:**

**Output:**




### Step 8: SSH Connection



**SSH Session Output:**


**Output:**


## Phase 5: Privilege Escalation



### Step 9: System Enumeration with LinPEAS



*
**Key Finding from LinPEAS:**


### Step 10: Analyzing the Writable Script



**Output:**


**Understanding File Permissions:**


**Why is this important?** 



### Step 11: Creating a Reverse Shell


**Command breakdown:**




**To find your IP address (attacking machine):**


### Step 12: Triggering the Reverse Shell



**Check your netcat listener** 

**Example successful connection:**


Congratulations! You now have root access!

### Step 13: Capturing the Flag



**Read the root flag:**


**Flag Output:**


## Summary and Key Learning Points

### What We Accomplished:


### Security Lessons:

