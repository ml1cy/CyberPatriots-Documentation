# CyberPatriots Documentation @ KRESA
CyberPatriots Documentation repository for the KRESA teams. This repository serves as a centralized archive for notes, practice tips, and scripts used during competition.
## First Year (2025)
* **Team Host:** Jim Goble
* **Advisor:** Mr. AD
* **Members:**
  - [Ijaz Ali](https://1cy.tech)
  - Brayden Buelow
  - Caiden Caswell
  - James Forton
  - Echo Ridenhour
### General Advice & Best Practices

To succeed in the competition and avoid life contemplation, keep the following in mind:

* **Commitment & Preparation:** Start preparing early, ideally before the summer. Only sign up if you can actually attend the competitions. 
* **The AI Rule:** AI is a helpful tool, particularly for answering forensics questions or generating initial scripts, don't rely on it for everything. You need to have a decent understanding of the scripts you use, AI can make mistakes.
* **Networking:** Networking is extremly difficult; try to recruit a dedicated member from the networking class if possible.
* **Practice:** Find and use practice VMs to learn basic hardening skills before the actual competition.

### Linux Guidelines

* **Script Everything:** Write scripts for every configuration file, user change, and basic hardening task. 
* **Test Thoroughly:** Always test your scripts on practice images. Bad scripts can corrupt your PAM file or break your entire image.
* **User Passwords:** Be extremely careful when editing the primary user's password, as doing it incorrectly can break your VM.

### Windows & Windows Server Guidelines

* **Longevity:** Windows 11 is only used in Rounds 1 and 2. Make sure to learn Windows Server or another discipline so you can continue contributing later in the competition.
* **Hardening Basics:** Key tasks include applying Group Policy settings, enabling firewalls and configuring rules, updating packages, and removing unused users/groups. 
* **Security:** Change default passwords immediately and ensure WPA2 encryption is enabled.
* **Troubleshooting:** If a script fails due to permissions, ensure you are running it as an administrator. If the scoring server is blocked, add an exception for the scoring IP in the firewall. Don't hit `WIN+L` while tabbed in a Windows Server VM because it logs you out, permanantly.
