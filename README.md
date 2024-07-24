# AIXCC DARPA Challenge 2024

AIxCC stands for Artificial Intelligence Cyber Challenge which aims to integrate AI and cyber-security to safeguard software. 

With the recent developments in AI, there is a great potential of making use of the advancement in the field of AI into the cybersecurity space and addressing cyber-attacks and cyber-crimes. 

Refer this page https://aicyberchallenge.com/ for more information on the competition and challenge projects. 

## Aim 
The aim of the challenge is to develop an end-to-end AI system to identify vulnerable code in the system and patch it autonmously without human intervention. 

To acheive this, the AIxCC DARPA moderators and developers have collaborated with top AI companies to assist the challengers in the development, and testing phase of their solutions. 

The challenge is restricted to C and Java language only. 

## Team 
Consists of 5 members - 
- [Jeff Huang](https://engineering.tamu.edu/cse/profiles/huang-jeff.html) 
- [Ting Dai](https://linkedin.com/in/ting-dai-b61579106/)
- [Heqing Hui](https://www.linkedin.com/in/heqing-huang-504712b6/)
- [Ze Sheng](https://www.linkedin.com/in/ze-sheng-294586222/)
- [Neha Manghnani](https://www.linkedin.com/in/neha-manghnani/)

## Challenges
AIxCC has provided example challenges which mocks the challenge problems which would be provided in the real competition. 

This is done to help competitors analyze the type of challenge projects which would presented, and to develop an AI system which would identify and patch the vulnerabilities in a similar challenge which would be presented in the competition.

## Experiments 
### [CP1 - Linux Kernel](https://github.com/aixcc-public/challenge-001-exemplar)

The first CP (challenge project) is to find the vulnerability added to the Linux Kernel source code. 
Linux Kernel CP was the example of a source code project in C language. 

Among the commits made to the linux kernel source code, one of the commits introduces a out of bounds access vulnerability (KASAN: slab-out-of-bounds) 

The experiments in the file 'cp1-linux-kernel-experiment.ipynb' consist of 
- prompting the LLM (GPT4o) to produce a input binary blob which would pass through the test harness file provided and trigger the KASAN : slab-out-of-bounds vulnerability.
- using LLM prompting to identify the commit to the source code (among the 5 commits) which introduces the vulnerability.
- getting a patch fix for the vulnerability by providing the error logs, commit diff and related source code to the LLM.

### CP2 - Jenkins

The second CP is to find the vulnerability added to the Jenkins source code. 
Jenkins CP was the example of a source code project in Java language. 

Among the commits made to the jenkins source code, one of the commits introduces a OS Command Injection bug in the source project. 

## Current Status 
Semifinal submission completed. Results due August 2025 at World's Top CyberSecurity Conference DEF-CON 2024
Finals would be held in August 2025. 
