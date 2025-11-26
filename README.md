# VPS-Zero
Dit is een samenstelling van 

## Script Features:
- Interactief Menu Systeem
- Volledige automatische installatie (optie 1)
- Individuele configuratie modules (2-16)
- Systeem status dashboard (20)
- Security audit met Lynis (21)

## Gebruik
- Interactief menu
sudo ./server-hardening.sh

# Volledige automatische installatie
sudo ./server-hardening.sh --full

# Help
sudo ./server-hardening.sh --help

## Implementeert de volgende taken:
- Docker Engine met security best practices
- UFW Firewall met rate limiting
- SSH hardening (custom poort, key-only auth)
- Fail2Ban met Docker protection
- Kernel security parameters (sysctl)
- Auditd met uitgebreide rules
- Automatische security updates
- Swap configuratie
- Filesystem hardening (noexec, nosuid)
- Logging & logrotate
- User management & PAM
- NTP synchronisatie
- Security tools (AIDE, Lynis, rkhunter)
- Docker security (user namespaces, seccomp)

## 🛡️ Veiligheidsfeatures:
- Automatische backups van configuraties
- Gedetailleerde logging (/var/log/server-hardening/)
- Color-coded output (info/success/warning/error)
- Bevestigingen voor kritieke acties
- Error handling met set -euo pipefail

Het script is volledig getest, gedocumenteerd en herbruikbaar. Klaar voor gebruik op alle Ubuntu VPS servers!


