# RECON PRO Dashboard

**RECON PRO** adalah dashboard interaktif berbasis web yang dirancang untuk membantu proses *reconnaissance* dalam bug bounty dan penetration testing. Tool ini berfungsi sebagai generator command yang terstruktur, cepat, dan efisien untuk berbagai tahapan pengumpulan informasi target.

Dengan antarmuka yang modern dan responsif, RECON PRO memungkinkan pengguna untuk menghasilkan command recon hanya dengan memasukkan domain target—tanpa perlu menghafal syntax dari berbagai tools.

## 🔍 Fitur Utama

* **Subdomain Enumeration**
  Generate command untuk tools seperti Subfinder, Amass, dan Assetfinder.

* **Port Scanning**
  Command siap pakai untuk Nmap, Masscan, dan scanning service.

* **HTTP Probing & Fingerprinting**
  Identifikasi teknologi, status code, dan live hosts dengan cepat.

* **URL & JavaScript Discovery**
  Kumpulkan endpoint tersembunyi dan file JS untuk analisis lebih lanjut.

* **WHOIS & DNS Recon**
  Informasi domain, DNS records, dan network footprint.

* **Vulnerability Scanning**
  Template command untuk Nuclei, SQLmap, DalFox, dan lainnya.

* **Bug Hunting Methodology**
  Panduan step-by-step workflow dari passive recon hingga reporting.

* **Wordlists Reference**
  Rekomendasi wordlist populer untuk berbagai kebutuhan brute-force.

## ⚡ Cara Kerja

1. Masukkan target domain (contoh: `example.com`)
2. Klik tombol **GENERATE**
3. RECON PRO akan menampilkan command lengkap untuk setiap tahap recon
4. Copy dan jalankan command tersebut di environment kamu

## 🎯 Tujuan

RECON PRO dibuat untuk:

* Mempercepat workflow recon
* Mengurangi human error dalam penulisan command
* Menjadi referensi all-in-one bagi bug hunter & pentester

## ⚠️ Disclaimer

Tool ini tidak menjalankan scanning secara langsung. Semua command yang dihasilkan harus dijalankan secara manual oleh pengguna di environment masing-masing.

Gunakan hanya pada target yang memiliki izin (*authorized testing*). Penggunaan tanpa izin adalah tanggung jawab pengguna.

## 🚀 Deployment

Project ini dapat di-deploy dengan mudah menggunakan platform seperti Vercel melalui integrasi dengan GitHub.

---

**RECON PRO — Work smarter, not harder.**
