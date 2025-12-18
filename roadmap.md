# 🛡️ Roadmap Cyber Security

**Target:** SOC Analyst / Junior Pentester (6 bulan)

Ringkasan singkat: roadmap ini terdiri dari modul mingguan yang disusun per bulan. Setiap minggu berisi tujuan, daftar tugas (checkbox), dan sumber belajar singkat. Sesuaikan tempo sesuai ketersediaan waktu (full-time / part-time).

## Cara pakai
- Bekerja per minggu: centang tugas saat selesai.
- Jika butuh latihan lebih, ulangi minggu terkait atau tambahkan mini-project.
- Simpan hasil analisis dan laporan di `GitHub` sebagai portfolio.

## Daftar Isi
- [Bulan 1 — Fundamental & Blue Team](#bulan-1---fundamental--blue-team)
- [Bulan 2 — SOC Analyst & SIEM](#bulan-2---soc-analyst--siem)
- [Bulan 3 — Web Security & AppSec](#bulan-3---web-security--appsec)
- [Bulan 4 — Advanced & Specialization](#bulan-4---advanced--specialization)
- [Bulan 5 — Portfolio & Apply](#bulan-5---portfolio--apply)
- [Bulan 6 — Interview & Continual Learning](#bulan-6---interview--continual-learning)

---

## Bulan 1 — Fundamental & Blue Team
Fokus: mindset security dan pondasi SOC

### Minggu 1 — Security Foundation
- [ ] Review protokol jaringan: TCP/IP, DNS, HTTP/HTTPS (perspektif keamanan)
- [ ] Pahami CIA Triad (Confidentiality, Integrity, Availability)
- [ ] Pelajari jenis serangan dasar: DoS, MITM, brute force
- [ ] Instalasi tools: `Wireshark`, `Nmap`, `Kali Linux` (VM)

Sumber singkat: dokumentasi Wireshark, Nmap cheat-sheet

### Minggu 2 — Linux & Log Analysis
- [ ] Pahami struktur log Linux (`/var/log`)
- [ ] Analisis file: `auth.log`, `syslog`
- [ ] Latihan command: `grep`, `awk`, `sed`, `journalctl`
- [ ] Simulasi login gagal dan telusuri log

### Minggu 3 — Network Monitoring
- [ ] Tangkap paket dengan `Wireshark`
- [ ] Identifikasi tanda port scanning dan traffic mencurigakan
- [ ] Latihan `nmap`: TCP scan, UDP scan, service detection

### Minggu 4 — Incident Response Dasar
- [ ] Pelajari Incident Response (IR) lifecycle
- [ ] Simulasi incident sederhana dan dokumentasi langkah
- [ ] Buat laporan incident (Markdown/PDF)
- [ ] Pengenalan MITRE ATT&CK (level high)

---

## Bulan 2 — SOC Analyst & SIEM
Fokus: monitoring, alerting, dan mulai pakai SIEM

### Minggu 5 — SIEM Basics
- [ ] Pahami konsep SIEM dan use case
- [ ] Opsional: instal ELK Stack (lokal/VM) untuk latihan
- [ ] Kenali sumber log penting: firewall, server, web server

### Minggu 6 — Alert & Detection
- [ ] Pelajari perbedaan false positive / true positive
- [ ] Buat rule deteksi sederhana (contoh: multiple failed logins)
- [ ] Mapping alert ke MITRE ATT&CK

### Minggu 7 — Malware & Threat Basics
- [ ] Kenali jenis malware secara umum
- [ ] Pahami konsep static vs dynamic analysis (konsep saja)
- [ ] Latihan mengidentifikasi IOC (Indicators of Compromise)

### Minggu 8 — SOC Simulation
- [ ] Ikuti lab simulasi (mis. TryBlueLabs, CyberDefenders)
- [ ] Dokumentasikan hasil analisis sebagai laporan
- [ ] Upload hasil ke GitHub (portofolio)

---

## Bulan 3 — Web Security & AppSec
Fokus: OWASP dan pengujian aplikasi web dasar

### Minggu 9 — OWASP Top 10
- [ ] Pelajari OWASP Top 10 (SQLi, XSS, CSRF, auth issues dsb.)

### Minggu 10 — Web Pentesting
- [ ] Pengenalan Burp Suite (Proxy, Repeater)
- [ ] Selesaikan latihan PortSwigger Academy (basic)
- [ ] Latihan manual testing pada aplikasi lab

### Minggu 11 — API & Authentication
- [ ] Pahami JWT, session vs token
- [ ] Pelajari broken access control dan skenario umum

### Minggu 12 — Mini Pentest Project
- [ ] Pilih target: lab atau dummy app
- [ ] Lakukan pentest kecil dan buat pentest report profesional
- [ ] Upload hasil ke GitHub

---

## Bulan 4 — Advanced & Specialization
Fokus: pilih jalur — SOC (Blue) atau Pentest (Red)

### Pilih jalur & contoh fokus
- **SOC Analyst (Blue Team)**
	- Advanced log correlation
	- Threat hunting
	- Case study breach
- **Pentester (Red Team)**
	- Advanced Burp techniques
	- Directory brute-force & discovery
	- Basic privilege escalation

Terapkan project mini sesuai jalur yang dipilih.

---

## Bulan 5 — Portfolio & Apply
Fokus: persiapan kerja dan perapihan portofolio

### Minggu 17–18 — Rapikan GitHub
- [ ] Rapikan repo proyek dan dokumentasi
- [ ] Tambahkan README dan ringkasan hasil analisis
- [ ] Perbarui LinkedIn dengan proyek relevan

### Minggu 19–20 — CV & Apply
- [ ] Siapkan CV khusus cybersecurity
- [ ] Lamar posisi: SOC Analyst / Junior Pentester

---

## Bulan 6 — Interview & Continual Learning
Fokus: persiapan interview, sertifikasi ringan, dan belajarlanjutan

### Contoh kegiatan
- [ ] Latihan teknikal interview (case studies, log triage)
- [ ] Pelajari sertifikasi entry-level (mis. CompTIA Security+ sebagai referensi)
- [ ] Rencana pembelajaran lanjutan: threat hunting, exploit dev, cloud security

---

## Catatan & Sumber
- Simpan bukti kerja (report, screenshots, script) di repo GitHub.
- Sumber rekomendasi: PortSwigger Academy, TryHackMe (lab web), Wireshark & Nmap docs, MITRE ATT&CK.
- **Referensi & link cepat**
- PortSwigger Academy (Web security labs & Burp): https://portswigger.net/academy
- OWASP Top 10: https://owasp.org/www-project-top-ten/
- TryHackMe (hands-on labs): https://tryhackme.com
- Hack The Box (labs & CTF): https://www.hackthebox.com
- Wireshark documentation: https://www.wireshark.org/docs/
- Nmap documentation / cheat sheet: https://nmap.org/book/man.html
- MITRE ATT&CK: https://attack.mitre.org
- Elastic Stack / ELK: https://www.elastic.co/what-is/elk-stack
- Burp Suite: https://portswigger.net/burp
- CompTIA Security+ (sertifikasi referensi): https://www.comptia.org/certifications/security
- Contoh sumber pelatihan SOC / blue team (opsional): Blue Team Labs, CyberDefenders (cari sesuai preferensi)

Jika Anda ingin, saya bisa:
- Menambahkan link referensi langsung ke resource.
- Mengubah tempo ke 3 bulan / 9 bulan.
- Menyiapkan template laporan incident dan pentest (Markdown).