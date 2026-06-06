##Firewall Configuration using UFW

## Objective
Configure and test firewall rules using UFW on Kali Linux.

## Commands Used

### Check Status
sudo ufw status

### Enable UFW
sudo ufw enable

### Block Telnet Port 23
sudo ufw deny 23

### Allow SSH Port 22
sudo ufw allow 22

### View Rules
sudo ufw status numbered

### Delete Rule
sudo ufw delete 1

## Outcome
Successfully configured firewall rules to block Telnet traffic and allow SSH traffic using UFW.
