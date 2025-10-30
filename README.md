# 🔒 Cyber Security Internship — Task 7  
## 🧩 Identify and Remove Suspicious Browser Extensions  

### 🎯 Objective  
To identify, analyze, and remove potentially harmful or unnecessary browser extensions in order to improve browser security, privacy, and performance.  

---

### 🛠️ Tools Used  
- **Google Chrome** (browser extension manager)  
- Manual verification via **Chrome Web Store** and online reputation checks  

---

### 🧭 Steps Followed  
1. Opened the Chrome extensions page → `chrome://extensions/`.  
2. Reviewed all installed extensions.  
3. Checked developer credibility, permissions, ratings, and last update date.  
4. Identified unused or suspicious extensions requesting excessive permissions.  
5. Removed or disabled high-risk or unnecessary extensions.  
6. Restarted the browser and noted performance changes.  
7. Researched how malicious extensions can impact privacy and data security.  

---

### 📋 Analysis of Installed Extensions  

| Extension | Purpose | Risk Level | Notes / Reasoning | Action |
|------------|----------|-------------|--------------------|--------|
| **Always Active Window – Always Visible** | Keeps windows always active | ⚠️ Medium | Spoofs browser visibility events; can cause abnormal behavior | **Removed** |
| **Burp Suite Navigation Recorder** | Captures navigation paths for Burp Suite | ✅ Low | Legitimate tool for web-app testing | **Kept** |
| **CGPA Calculator** | GPA calculator & chart | ⚠️ Medium | Unknown developer; unnecessary permissions | **-** |
| **Dark Mode – Night Eye** | Adds dark theme for web pages | ✅ Low | Trusted productivity tool | **Kept** |
| **Enable Copy Anywhere** | Bypasses copy restrictions | 🚨 High | Injects scripts; violates site policies | **Removed** |
| **EPUBReader** | Reads EPUB files in-browser | ✅ Low | Safe; limited permissions | **Kept** |
| **Focus To-Do (Pomodoro Timer)** | Task & timer tool | ⚠️ Medium | Safe but not essential | **Disabled** |
| **Google Docs Offline** | Enables offline editing | ✅ Low | Official Google extension | **Kept** |
| **Google Scholar PDF Reader** | Enhances scholarly PDF reading | ✅ Low | Verified developer | **Kept** |
| **SEOquake** | SEO metrics tool | ⚠️ Medium | Requires access to visited pages; check source | **Kept** (official) |
| **uBlock Origin Lite** | Ad & tracker blocker | ✅ Low | Trusted open-source blocker | **Kept** |

---

### 🔍 Findings  
- **11 extensions** reviewed.  
- **2 high-risk** extensions (*Enable Copy Anywhere**, **Always Active Window**) removed.  
- Performance and browser startup speed improved.  
- Remaining extensions are from **verified sources** and have justified permissions.  

---

### 💡 Key Learnings  
- Extensions can access sensitive data if granted excessive permissions.  
- Always verify developer credibility and read permissions before installation.  
- Free VPNs and copy-enabling tools are common sources of **privacy leakage**.  
- Regular audits help maintain **browser integrity and performance**.  


### 🎯 Outcome  
After the analysis, only trusted and necessary extensions remain.  
This task improved awareness of **browser-level threats**, **permission auditing**, and **safe extension management practices**, resulting in a more secure and efficient browsing environment.  

---

### 📁 Files in Repository  
| File | Description |
|------|--------------|
| `README.md` | Task overview and findings |
| `Report_Task7_Browser_Extension_Analysis.pdf` | Detailed report (optional) |
