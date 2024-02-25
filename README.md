<img src="assets/cybersecurity.webp" alt="Cybersecurity" style="width: 380px;" align="right">

# Cybersecurity | Quickstarts
Cybersecurity Quickstarts

## Checklist
### General
- [ ] Exclude sensitive data from the logs (e.g.: session details, access key...)
- [ ] Delete *things* you don't need anymore that could be exploited (e.g.: unused accounts, applications, daemon 😈 services...)
- [ ] Make sure none of the passwords you have in your systems are the default ones (remember that e-commerce... yes... exactly)
- [ ] Use SELinux or AppArmor to secure your system (**!IMPORTANT!** make sure that SELinux is enable `getenforce` or `sestatus`)
### Network
- [ ] Block ports that are not used
- [ ] Block ports from the outside for daemons 😈 and applications (e.g.: MySQL port 3306, PostgreSQL port 5432, ElasticSearch ports 9200 & 9300, etc)
- [ ] Removed any access to the network for applications or daemons 😈 that don't need it
