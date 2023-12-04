# Types of Privileged Accounts You Should Be Aware Of

## ROOT or Super User Accounts

- **Use:** Has the highest level of access and control over a system or network. Used for configuration, installation of system maintenance, software, or updates.
  
- **Attack Vectors:** Attackers often target these accounts through vulnerabilities in operating systems or through social engineering to obtain or exploit root access.
  
- **How to Protect:**
  - Implement strong authentication.
  - Regularly update the OS.
  - Use intrusion detection systems (IDS/IPS).
  - Restrict access to trusted administrators.

## Admin Accounts

- **Use:** Prevalent in Windows Administrator environments, with extensive access privileges to manage user accounts, install software, and configure system settings.
  
- **Attack Vectors:** Attackers may exploit vulnerabilities, use brute force attacks, or engage in privilege escalation to compromise administrator accounts.
  
- **How to Protect:**
  - Enforce strong password policies.
  - Implement two-factor authentication (2FA).
  - Restrict administrative access to necessary personnel.
  - Regularly patch Windows systems.

## Database Admin Accounts

- **Use:** Managed by Database Administrators (DBAs) to control access, run backups, and optimize database performance.
  
- **Attack Vectors:** Attackers may exploit weak database configurations, SQL injection vulnerabilities, or gain access through phishing attacks on DBAs.
  
- **How to Protect:**
  - Use strong database access controls.
  - Regularly update the database software.
  - Apply least privilege principles.
  - Monitor database activity.

## Service Accounts

- **Use:** Used by applications or services to access databases, servers, and other resources. Often configured with elevated privileges.
  
- **Attack Vectors:** Attackers can compromise these accounts through vulnerabilities in the applications they serve, weak or leaked credentials, or privilege escalation.
  
- **How to Protect:**
  - Protect the applications.
  - Limit service account privileges to what's necessary.
  - Secure and regularly rotate service account passwords.
  - Monitor service account activity.

## Application Accounts

- **Use:** Used to run specific applications or services with predefined permissions for specific tasks.
  
- **Attack Vectors:** Attackers may target application vulnerabilities, exploit weakly configured permissions, or use stolen or leaked credentials for unauthorized access.
  
- **How to Protect:**
  - Secure the applications.
  - Apply the principle of least privilege to application accounts.
  - Enforce strong authentication.
  - Regularly monitor and audit application account activity.

## Vendor or Third-Party Accounts

- **Use:** Privileged access provided to third-party vendors supporting organizations or services.
  
- **Attack Vectors:** Attackers can compromise these accounts through supply chain attacks, social engineering, or exploiting weaknesses in the vendor's security practices.
  
- **How to Protect:**
  - Vet and audit third-party vendors.
  - Restrict external access.
  - Require strong authentication and access controls for third-party accounts.
  - Monitor third-party activity.

## Privileged User Accounts

- **Use:** Used by employees or administrators who need elevated access for specific tasks, such as network configuration, management, security, or server monitoring.
  
- **Attack Vectors:** Insider threats, social engineering, or phishing attacks may be used to compromise privileged user accounts.
  
- **How to Protect:**
  - Educate employees on security best practices.
  - Enforce strong password policies.
  - Regularly monitor and audit privileged user account activity.
  - Implement user behavior analytics.

## Emergency Break-Glass Accounts

- **Use:** Typically reserved for emergency access to systems or data when standard access is unavailable.
  
- **Attack Vectors:** Attackers may target these accounts through weak password management, unauthorized access, or exploiting emergency access procedures.
  
- **How to Protect:**
  - Encrypt and protect emergency account credentials.
  - Restrict access to break glass accounts to a few trusted individuals.
  - Implement strong multi-factor authentication for emergency access.

## Shared Accounts

- **Use:** Typically used by multiple users for specific tasks, often as shared access for designated purposes.
  
- **Attack Vectors:** Password sharing, weak access controls, unauthorized access, and lack of individual accountability.
  
- **How to Protect:**
  - Implement strong access controls.
  - Enforce individual accountability for shared account usage.
  - Regularly change shared account passwords.
  - Audit shared account activity.
