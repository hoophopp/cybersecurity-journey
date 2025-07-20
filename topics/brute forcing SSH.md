## Brute forcing SSH | today note's
---
---
- `Hydra` (thc-hydra): very popular for SSH brute forcing.

- `Medusa`: similar tool to Hydra.

- `Ncrack`: specialized in network authentication crack-Ing.

- `John the Rippe` (ssh used)§§

- `Patator`: versatile brute force tool.

```hydra -l username -P /path/to/passwordlist.txt ssh://target_ip```

# SSH servers can detect crackers: 
- Fail2ban and similar tools monitor failed login attempts and block IPs that fail too many times.
- Key-based authentication
- might require 2FA


  
# Insta or Fb can detect aso :
- use capatcha
- rate limiting
- might require 2FA
- block ip's



# How can hackers avoid detection:
- spread their attempts across lots of different IP addresses.
- try only a few guesses per hour or day
- use Tor and strong vpn's
- use leaked password lists or stolen SSH private keys
- finding bugs without using crackers
 
---

