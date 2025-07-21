# Leaked passwords or SSH keys:
## Common Causes

### 1. Hacks
Attackers steal user databases, which may include:
- Passwords (often hashed, but sometimes plaintext)
- SSH keys
- API tokens

### 2. GitHub Repositories
Sensitive information could happen to be accidentally uploaded to public repos by the developers in particular, such as:
- Private SSH keys
- Environment variables
- Hardcoded passwords

> ⚠️ Tip: **In order to scan all of your code for secrets, use tools like [GitGuardian]**(https://www.gitguardian.com/).

### 3. Phishing (Fake Emails ..)
Hackers trick users when they impersonate legitimate services in order to reveal:
- Passwords
- SSH private keys
- 2FA codes

### 4. Password Reuse
Many users face increased risk reusing passwords across platforms if one site is compromised.

> ✅ Fix: **Use a password manager for each site to store unique, strong passwords that are generated.**
