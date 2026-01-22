---
layout: default
title: Grigoris Giannis
---
<div class="cv-header">

  <h1>Grigoris Giannis</h1>
  <p class="cv-title">
    Electronics Engineer · IT Support Specialist
  </p>

  <p class="cv-meta">
    📍 Athens, Greece · 📧 greg_giannis@hotmail.com · 📞 +30 210 211 6954 · 📱 +30 697 797 9884
  </p>

  <div class="cv-actions">
    <a href="cv-el.html" class="cv-btn">🇬🇷 Ελληνικά</a>
    <a href="/greg-giannis/assets/cv-en.pdf" class="cv-btn cv-btn-secondary">
      📄 Λήψη PDF
    </a>
  </div>

</div>
<!-- Floating dark mode toggle -->
<button id="darkModeToggle" class="floating-toggle">🌙</button>

<style>
/* Light mode */
body {
  background-color: #ffffff;
  color: #000000;
}

/* Dark mode */
body.dark-mode {
  background-color: #121212;
  color: #e0e0e0;
}

body.dark-mode a {
  color: #80cbc4;
}

/* Floating toggle button */
.floating-toggle {
  position: fixed;
  top: 16px;
  right: 16px;
  background-color: #f0f0f0;
  color: #000000;
  border: 1px solid #ccc;
  padding: 10px 12px;
  cursor: pointer;
  border-radius: 50%;
  font-size: 20px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.25);
  transition: background-color 0.3s, color 0.3s, transform 0.2s;
  z-index: 9999;
}

/* Dark mode button */
body.dark-mode .floating-toggle {
  background-color: #333333;
  color: #ffffff;
  border: 1px solid #666;
}

/* Hover effect */
.floating-toggle:hover {
  transform: scale(1.1);
}
</style>

<script>
// Restore saved preference
if (localStorage.getItem("darkMode") === "enabled") {
  document.body.classList.add("dark-mode");
  document.getElementById("darkModeToggle").textContent = "☀️";
}

// Toggle on click
document.getElementById("darkModeToggle").addEventListener("click", function () {
  document.body.classList.toggle("dark-mode");

  if (document.body.classList.contains("dark-mode")) {
    this.textContent = "☀️"; // Sun icon
    localStorage.setItem("darkMode", "enabled");
  } else {
    this.textContent = "🌙"; // Moon icon
    localStorage.setItem("darkMode", "disabled");
  }
});
</script>

---

## Professional Summary
Electronics Engineer with extensive experience in IT support, telecommunications,
enterprise networking, and Microsoft & Linux systems.
Strong background in troubleshooting, corporate customer support,
and field technical services.

---

## Professional Experience

### Cosmote Telekom — *Corporate Technical Support*
**1-2-2024**
- Support for fixed telephony and Internet services
- Corporate network troubleshooting
- Customer-facing technical support
  
### Vodafone — *Corporate Technical Support*  
**2017 – 2022**
- Support for fixed telephony, Internet, and IPTV services
- Corporate network troubleshooting
- Customer-facing technical support

### Forthnet S.A. — *Technical Support Engineer*  
**2010 – 2016**
- Support for telephony, Internet, and NOVA services

### CPI S.A. — *Dell Systems Engineer*  
**2006 – 2009**
- Certified Dell technician (servers, desktops, laptops)
- Installation and maintenance of Dell systems
- Field service engineer

### NET SALES S.A. (BYTE Group) — *Hardware Technician*  
**2003 – 2004**
- PC hardware service
- Support for Singular ERP applications
- Remote and on-site support

### N. Avgerinopoulos Group — *IT Support Specialist*  
**2001 – 2003**
- Network support for vocational schools (IEK, TEE)
- IT support for retail branches nationwide

### Microland Computers S.A. (ALTEC Group) — *IT Technician*  
**1999 – 2001**
- PC assembly and service
- Installation of HP, COMPAQ, IBM servers
- Field technical support

### Informatics H/Y S.A. — *Internship*  
**1997 – 1998**
- PC assembly
- Mass OS deployment over network

---

## Education

**BSc in Electronics Engineering**  
Piraeus University of Applied Sciences  
**1993 – 1999**

**Thesis:**  
Design and Development of DCS1800 Mobile Telephony System (COSMOTE)

---

## Certifications
- Microsoft Windows Server 2003 Network Infrastructure (070-291)
- Managing Windows Server 2003 (070-290)
- Windows XP Professional (070-270)
- Dell Certified Systems Expert – EMEA ESF Level 2

---

## Technical Skills

**Operating Systems**
- Windows NT → 11
- Windows Server 2000 → 2016
- Linux (Ubuntu, Fedora, Deepin)
- macOS

**Tools & Technologies**
- VMware Workstation
- Microsoft Office
- Adobe Photoshop
- DaVinci Resolve
- Adobe Premiere Pro

---

## Languages
- English — Very good (Lower)

---

© Grigoris Giannis
















