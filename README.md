# WordPress-security-portfolio-samuel
A practical WordPress security portfolio showcasing vulnerability scanning, malware cleanup preparation, website hardening, and 2FA setup using real tools like iThemes Security and MalCare.
# 🔐 WordPress Security Analyst Portfolio – Leo

Welcome to my WordPress Security Portfolio. This repository showcases my practical experience handling core security tasks using real tools on a live WordPress site.

---

## 🛠️ Tools Used
- [iThemes Security](https://wordpress.org/plugins/better-wp-security/)
- [MalCare Malware Scanner](https://wordpress.org/plugins/malcare-security/)
- .htaccess (for header config)
- [SecurityHeaders.com](https://securityheaders.com)

---

## ✅ 1. Fixing Missing Security Headers

**Problem:**  
Scan showed missing headers like `X-Frame-Options`, `X-Content-Type-Options`, `Strict-Transport-Security`.

**Solution:**  
Configured headers via `.htaccess` and verified using SecurityHeaders.com.

**Screenshots:**  
- Before: ![Headers Before](screenshots/headers-before.png)  
- After: ![Headers After](screenshots/headers-after.png)  
- Config: ![HTACCESS Config](screenshots/htaccess-config.png)

---

## ✅ 2. Malware Scan (MalCare)

**Task:**  
Scanned the site using MalCare to detect malware or infections.

**Result:**  
No malware found, but simulated cleanup workflow prepared.

**Screenshots:**  
- ![Malware Scan Clean](screenshots/malcare-scan-clean.png)  
- ![MalCare Dashboard](screenshots/malcare-dashboard.png)

---

## ✅ 3. Website Hardening

**Task:**  
Enabled key security hardening options in iThemes Security:
- Disable file editing
- Block XML-RPC
- Hide login URL
- Disable directory browsing

**Screenshots:**  
- Before: ![Hardening Before](screenshots/hardening-before.png)  
- After: ![Hardening After](screenshots/hardening-after.png)

---

## ✅ 4. Two-Factor Authentication (2FA)

**Task:**  
Scan detected administrator users without 2FA.

**Solution:**  
Enabled 2FA via iThemes Security and verified setup.

**Screenshots:**  
- Scan Warning: ![2FA Warning](screenshots/2fa-scan-warning.png)  
- Settings: ![2FA Settings](screenshots/2fa-settings.png)  
- Applied: ![2FA Applied](screenshots/2fa-applied.png)

---

## 📌 Summary

This portfolio demonstrates:
- Vulnerability detection
- Real tool usage
- Security improvement actions
- Documentation for client or employer review

---

## 👨‍💻 About Me

I’m samuel a junior WordPress Security Analyst focused on practical, hands-on improvements. My goal is to secure WordPress sites through scanning, hardening, and cleanup.

Feel free to reach out or collaborate.
