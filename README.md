# TOOL_DOWNLOADER_TOOLS_VULN_CHECKER

📌 Deskripsi

TOOL_DOWNLOADER_TOOLS_VULN_CHECKER.sh adalah script Bash yang digunakan untuk
mengunduh, menginstal, dan menyiapkan berbagai tools vulnerability checker
secara otomatis untuk keperluan security testing yang legal.

Tool ini cocok untuk:

- Bug bounty
- Pentest lab pribadi
- Pengujian server milik sendiri
- Edukasi keamanan siber

---

⚠️ Disclaimer

Script ini HANYA BOLEH DIGUNAKAN pada:

- Website milik sendiri
- Server lab
- Target yang memiliki izin resmi

Penggunaan tanpa izin adalah ILEGAL dan menjadi tanggung jawab pengguna sepenuhnya.

---

🛠️ Requirements

- Linux (Ubuntu / Debian / Kali / Termux)
- Bash shell
- Akses internet
- Hak akses root (disarankan)

Package minimum:
apt update && apt install -y bash curl wget git unzip

---

📥 Instalasi

1. Clone repository:
git clone https://github.com/asepyuta-sudo/vuln_toolkit_installer.git

2. Masuk ke direktori tool:
cd vuln_toolkit_installer   # atau nama folder hasil clone

3. Beri izin eksekusi:
chmod +x TOOL_DOWNLOADER_TOOLS_VULN_CHECKER.sh

---

▶️ Cara Menjalankan

Jalankan script dengan perintah:
./TOOL_DOWNLOADER_TOOLS_VULN_CHECKER.sh

Jika terjadi error permission atau environment:
bash TOOL_DOWNLOADER_TOOLS_VULN_CHECKER.sh

---

📂 Struktur Direktori

Setelah instalasi berhasil, struktur folder akan terlihat seperti ini:

TOOL_DOWNLOADER_TOOLS_VULN_CHECKER/
├── TOOL_DOWNLOADER_TOOLS_VULN_CHECKER.sh
├── tools/
│   ├── nmap/
│   ├── sqlmap/
│   ├── nuclei/
│   ├── nikto/
│   └── ffuf/
└── README.md

Selamat mencoba dan tetap gunakan secara etis! 🚀
