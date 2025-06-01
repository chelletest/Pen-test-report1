**Only scan applications you have permission to test. Unauthorized scanning may be illegal and unethical.**
# Pen-test-report
# OWASP ZAP – Basic Web Application Security Test

This project demonstrates how to use OWASP ZAP (Zed Attack Proxy) to identify potential security vulnerabilities in a web application.

##  What is OWASP ZAP?

OWASP ZAP is a free, open-source security scanner used to find vulnerabilities in web applications. It is maintained by the OWASP Foundation and is beginner-friendly, with both GUI and API interfaces.

## Tools Used

- **OWASP ZAP**: For passive and active scanning
- **Firefox** or **Chrome**: Configured to use ZAP as a proxy
- **Test Target**: Example vulnerable app like [http://testphp.vulnweb.com](http://testphp.vulnweb.com)

## How to Use This

1. **Install OWASP ZAP**

   ```bash
   sudo add-apt-repository ppa:owasp-zap/ppa
   sudo apt update
   sudo apt install zaproxy
2. **Launch ZAP**

    Zaproxy
4. **Set up your browser to use ZAP as a proxy**

    HTTP Proxy: 127.0.0.1
    Port: 8080

6.  **Explore the target website manually through your browser.**

    ZAP will capture and display all traffic.

7.  **Use the Spider and Active Scan in ZAP to automatically explore and test the site.**

8.  **View alerts** in the Alerts tab and generate reports under:

    Report > Generate Report



