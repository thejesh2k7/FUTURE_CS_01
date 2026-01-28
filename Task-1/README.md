# Task-1 – Security Analysis Report

## 👤 Intern Details
**Name:** Koduru Thejesh Naidu  
**CIN ID:** FIT/JAN26/CS5575  
**Program:** Cyber Security Internship – Future Interns  

---

## 🎯 Objective  
Analyze the website **https://www.iplt20.com** using:  
- SecurityHeaders.com  
- OWASP ZAP  

to identify missing headers, vulnerabilities, and generate a security report.

---

## 🛠 Tools Used  
- SecurityHeaders.com  
- OWASP ZAP 2.17.0  
- Microsoft Edge / Chrome  
- Snipping Tool  

---

## 📊 Summary of Findings

### 1️⃣ Security Headers Result  
**Final Grade: C**

**Headers Present:**  
- ✔ Strict-Transport-Security  
- ✔ X-Content-Type-Options  
- ✔ X-Frame-Options  

**Missing Headers:**  
- ❌ Content-Security-Policy  
- ❌ Referrer-Policy  
- ❌ Permissions-Policy  

---

### 2️⃣ ZAP Scan Results  
- Successfully crawled the IPL website  
- Discovered endpoints:  
  - `/assets/`  
  - `/matches/`  
  - `/stats/`  
  - `/photos/`  
  - `/videos/`  
- Generated full ZAP HTML scan report  

---

## 📁 Files Included in Task-1  
- `SecurityHeaders_IPL.png`  
- `ZAP_SiteStructure.png`  
- `ZAP_Report.html.html`  
- `README.md`  

---

## ✅ Conclusion  
Completed the basic security assessment for Task-1.  
Learned website header analysis, scanning with OWASP ZAP, documentation, and GitHub submission.
