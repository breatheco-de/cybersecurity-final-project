# 📝 Solution

> ⚠ If at any point you feel stuck and cannot progress, you may refer to the provided solution. However, we encourage you to attempt to resolve the vulnerabilities on your own first, as this will provide you with a more enriching experience in cybersecurity analysis.

Now, to approach this project as a cybersecurity analyst for 4Geeks Academy, you will need to identify and resolve the issues. Below are the vulnerabilities present on the machine that you should investigate.

### Vulnerabilities Configured on the Machine

- **MySQL Configuration:** A database user has been intentionally created with a weak password. Investigate how this configuration can compromise database security.

- **FTP Configuration:** The FTP server is misconfigured, allowing insecure access that exposes files and services. Examine the access permissions and server configuration.

- **SSH Configuration:** SSH access has been configured to allow authentication with weak passwords. Evaluate the authentication method and its strength.

- **Unnecessary Open Ports:** Verify that there are unnecessary open ports, which increase the attack surface of the system. Identify which ports these are and the associated services.

- **Incorrect Permissions on wp-config.php:** The `wp-config.php` file, which contains critical database credentials, is exposed to unauthorized users due to overly permissive permissions. Review the permissions assigned to this file.

- **Listable Web Directory:** The web directories have been configured to be listable, allowing attackers to explore and access files that should be hidden or protected. Investigate the web server configuration to understand how this indexing is permitted.

These instructions will guide you in identifying the vulnerabilities present on the server. Once you have documented them, you can proceed to prepare a report on your findings.
