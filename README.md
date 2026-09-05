# Network Troubleshooting Guide

## Checklist Dasar

### 1. Physical
- Cek power.
- Cek kabel LAN.
- Cek indikator link.
- Cek port switch.

### 2. IP Configuration
Windows:
```powershell
ipconfig /all
```

Linux:
```bash
ip addr
ip route
```

### 3. Connectivity
```bash
ping 192.168.1.1
ping 8.8.8.8
```

### 4. DNS
```bash
nslookup google.com
```

### 5. Route
Windows:
```powershell
tracert 8.8.8.8
```

Linux:
```bash
traceroute 8.8.8.8
```

## Dokumentasi
Setiap troubleshooting sebaiknya mencatat:
- waktu kejadian
- perangkat/user
- gejala
- hasil pengecekan
- tindakan
- hasil akhir
- escalation jika ada

> Contoh ini dibuat sebagai simulasi portfolio dan tidak menggunakan konfigurasi jaringan perusahaan.
