<!-- hide -->
# Cybersecurity Final Project

> By [@rosinni](https://github.com/rosinni) and [other contributors](https://github.com/breatheco-de/cybersecurity-final-project/graphs/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![build by developers](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=twitter)](https://twitter.com/4geeksacademy)

*Estas instrucciones estan [disponibles en español](https://github.com/breatheco-de/cybersecurity-final-project/blob/main/README.es.md)*

### Before you start...

> We need you! These exercises are built and maintained in collaboration with contributors such as yourself. If you find any bugs or misspellings please contribute and/or report them.
<!-- endhide -->

<onlyfor saas="true" withBanner="false">
# 🌱 How to Start This Project

For this final project, you will assume the role of a cybersecurity analyst responsible for restoring and protecting a critical server that has been compromised at 4Geeks Academy. You will be provided with a [hacked machine](https://storage.googleapis.com/breathecode/virtualbox/debian-final-project.ova) that simulates a key company server, and your task will be to re-establish its security, fix the exploited vulnerabilities, and ensure its optimal functionality. The exercise is divided into three phases that will test your skills in forensic analysis, vulnerability detection and remediation, and incident response.

- **Phase 1 - Hack Correction**  
In the first phase, you will conduct a forensic analysis of the incident, identify the vulnerabilities exploited by the attacker, and block the exploit to prevent further escalation of the attack.

- **Phase 2 - Detection and Correction of a New Vulnerability**  
In the second phase, you will scan the system for an additional vulnerability, different from the one previously exploited. Once detected, you will exploit the vulnerability in a controlled manner to understand its impact, escalate its privileges, fix it, and create a report that explains the entire process.

- **Phase 3 - Incident Response Plan and Certification**  
The final phase involves designing an incident response plan based on industry best practices, such as the NIST recommendations. As part of this exercise, you will develop an Information Security Management System (ISMS) in accordance with the ISO 27001 standard, which will include measures to prevent data leaks through Data Loss Prevention (DLP) policies.
</onlyfor>

## 📝 Instructions

### Phase 1: Recognition and collection of evidence

**Objective:** Conduct a forensic analysis to block the exploit, fix the vulnerability, and prevent the attacker from escalating.

1. Identify which services were compromised and how the attacker accessed the server. You can use tools like `grep` to review system logs (for example, `/var/log/auth.log` for SSH connections).
2. Identify suspicious files, running processes, and any unusual modifications in the system.
3. Perform a scan of the server to detect rootkits or malware.
4. Block the exploit and prevent escalation. Temporarily stop compromised services (`systemctl stop service`) if necessary.
5. Revert changes made by the attacker (remove unauthorized users, eliminate backdoors, close unnecessary ports).
6. Update and correct security configurations (update packages, change passwords, improve firewall settings if necessary).
7. Prepare a detailed report that includes the measures taken to mitigate the attack and prevent escalation. Additionally, include recommendations on how to prevent future attacks of a similar nature.


### Phase 2: Detect and Fix a Different Vulnerability

**Objective:** Scan, detect, and exploit a vulnerability different from the one previously exploited and create a report that explains the entire process.

1. Perform a complete scan of the system using tools like `Nmap`.
2. Detect a vulnerability unrelated to the previous hack, such as a misconfiguration in Apache, unnecessary open ports, or an exposed service, and exploit this detected vulnerability.
3. Document the exploitation process and the steps taken to compromise the service or escalate privileges.
4. Apply measures to fix the found vulnerability, such as closing ports, changing security configurations, or restricting access.
5. Prepare a detailed report that includes the detected vulnerability, the exploitation process, and the measures applied to correct it.


### Phase 3: Incident Response Plan and Certification

**Objective:** Design an incident response plan based on best practices and develop an Information Security Management System (ISMS) in accordance with the ISO 27001 standard.

1. Develop a response plan based on the NIST SP 800-61 guidelines, which includes how to identify, contain, eradicate, and recover from future security incidents.
2. Detail how the organization would respond to an attack similar to the one that occurred and how to prevent recurrence.
3. Identify and document data protection mechanisms, such as the use of regular backups, encryption of sensitive data, and the implementation of strict access controls.
4. Implement an ISMS (ISO 27001). Develop an Information Security Management System (ISMS) that complies with ISO 27001 standards, including risk analysis, definition of security policies, and action plans to protect the company’s critical information.


## 📦 How to Submit This Project?

- [ ] Create a **network diagram** using tools like Packet Tracer that reflects the current network topology and recommended changes.
- [ ] Present the **Debian virtual machine** with services correctly configured and issues resolved.
- [ ] Prepare a **penetration testing report**.
- [ ] Prepare a **security incident report** detailing the forensic analysis, corrective actions, and preventive measures taken.
- [ ] Develop a **recovery plan** to ensure the continuity of the company’s critical services in case of an incident.
- [ ] Create an **executive presentation** for management, explaining what happened, the actions taken, and future recommendations.


<!-- hide -->
## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Rosinni Rodríguez (rosinni)](https://github.com/rosinni) contribution: (build-tutorial) ✅, (documentation) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr),  contribution: (bug reports) 🐛

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind are welcome!

This and many other exercises are built by students as part of the 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sánchez](https://twitter.com/alesanchezr) and many other contributors. Find out more about our [Full Stack Developer Course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer), and  [Data Science Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/datascience-machine-learning). You can alse deepdive in the world of cybersecurity with our [Cybersecurity Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/cybersecurity)
<!-- endhide -->

