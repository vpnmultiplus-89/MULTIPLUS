# MULTIPLUS VPN PANEL

MULTIPLUS adalah script panel VPN berbasis **Shell (bash)** untuk manajemen akun VPN secara otomatis, ringan, dan mudah digunakan.

---

## ✨ Fitur Utama

- ✅ Instalasi otomatis (1 klik)
- ✅ Panel manajemen user
- ✅ Tambah / edit / hapus user
- ✅ Trial akun otomatis (per jam)
- ✅ Expired berbasis datetime
- ✅ Status ACTIVE / EXPIRED
- ✅ Hitung bandwidth (MB / GB / TB)
- ✅ Monitoring CPU, RAM, dan bandwidth realtime
- ✅ Backup & restore data
- ✅ Sinkronisasi harian
- ✅ NAT redirect otomatis & persist
- ✅ Tanpa sistem lock user
- ✅ Custom nama panel saat instalasi
- ✅ Menu interaktif & rapi

---

## 📂 Struktur File

```
MULTIPLUS/
├── install.sh
├── install-histeria.sh
├── menu.zip
├── system.zip
└── README.md
```

---

## 🚀 Cara Install

Login ke VPS sebagai **root**, lalu jalankan:

```bash
apt update && apt install -y git
git clone https://github.com/vpnmultiplus-89/MULTIPLUS.git
cd MULTIPLUS
chmod +x install.sh
./install.sh
```

Ikuti instruksi saat proses instalasi berjalan.

---

## 🧰 Requirement

- Ubuntu 20.04 / 22.04
- Akses root
- VPS fresh (disarankan)
- Koneksi internet stabil

---

## 🛠 Perintah Penting

Cek status service:
```bash
systemctl status zivpn
```

Restart service:
```bash
systemctl restart zivpn
```

---

## ⚠️ Catatan

- Jika panel tidak bisa diakses:
  - Pastikan service berjalan
  - Periksa firewall / port
  - Pastikan tidak bentrok dengan service lain
- Jika file terhapus, jalankan ulang installer

---

## 📌 Informasi

Project ini dibuat untuk pembelajaran dan pengelolaan server pribadi.  
Gunakan dengan bijak dan sesuai aturan yang berlaku.

---

## ⭐ Dukungan

Jika project ini bermanfaat:
- Beri ⭐ Star pada repository
- Fork untuk pengembangan sendiri

---

**Author:** vpnmultiplus-89  
**Language:** Shell  
**Status:** Active Development
