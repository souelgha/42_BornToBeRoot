# 42_BornToBeRoot
Create a secured Virtual Machine using VirtualBox
Creating and securing a debian VM.

## Monitoring:
- cron task :
  _ */10 * * * * sh /root/monitoring.sh | wall

## service:
An SSH server on port 4242

## Config Files
- Password policy (with pwquality)
  - /etc/pam.d/commom-password
  - /etc/security/pwquality.conf
- SSH
  - /etc/ssh/sshd_config
- Sudo
  - /etc/sudoers
