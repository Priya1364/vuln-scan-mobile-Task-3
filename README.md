# vuln-scan-mobile-Task-3
Mobile-only vulnerability scan for internship Task 3
🔎 Vulnerability Scan Report  

Target: scanme.nmap.org  
Date: 25-09-2025  
Tool Used: SSL Labs, Security Headers  

Findings:
1. SSL Labs → Grade B (supports TLS 1.0, weak).  
2. Security Headers → Missing Content-Security-Policy.  
3. Open ports: 22 (SSH), 80 (HTTP).  

Severity:
- Medium: Weak TLS protocol.  
- High: Missing security headers.  

✅ Recommendation:
- Disable old TLS versions.  
- Add strict security headers.  
- Close unused ports.
