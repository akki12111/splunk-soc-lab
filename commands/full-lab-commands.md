# Full Lab Commands

## Nmap Scan (Kali)

nmap -Pn -p 22 <TARGET-IP>

## Hydra SSH Brute Force

hydra -l testuser -P passwords.txt ssh://<TARGET-IP>


## Splunk Search

index=linux sourcetype=suricata:json event_type=alert


