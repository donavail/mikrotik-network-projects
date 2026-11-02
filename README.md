# Proyek Jaringan MikroTik

Repositori ini berisi dokumentasi proyek dan praktik konfigurasi jaringan komputer menggunakan perangkat MikroTik selama masa perkuliahan di Program Studi Sistem Komputer, Universitas Sriwijaya. Materi yang didokumentasikan mencakup implementasi DHCP Server pada jaringan berbasis Bridge, konfigurasi Network Address Translation (NAT) menggunakan Masquerade PAT, serta manajemen bandwidth menggunakan algoritma Stochastic Fairness Queuing (SFQ). Setiap proyek dilengkapi dengan laporan yang menjelaskan tujuan, perancangan topologi, tahapan konfigurasi, dan hasil pengujian sebagai dokumentasi penerapan konsep jaringan komputer secara praktis.

## Dokumentasi Proyek

### 1. DHCP Server pada Jaringan Bridge
Implementasi DHCP Server pada infrastruktur jaringan berbasis Bridge untuk mendistribusikan alamat IP secara otomatis kepada perangkat yang terhubung.

Folder: `dhcp-server-bridge/`

### 2. Konfigurasi Masquerade PAT
Implementasi Masquerade Port Address Translation (PAT) pada MikroTik RB941 agar beberapa perangkat dalam jaringan lokal dapat mengakses internet menggunakan satu alamat IP publik.

Folder: `masquerade-pat/`

### 3. Manajemen Bandwidth Menggunakan SFQ
Penerapan algoritma Stochastic Fairness Queuing (SFQ) pada MikroTik RB941 untuk mengatur distribusi bandwidth secara lebih merata antar pengguna jaringan. Proyek ini juga mencakup konfigurasi Bridge, DHCP Server, dan NAT.

Folder: `bandwidth-management-sfq/`

## Perangkat dan Perangkat Lunak

- MikroTik RB941
- MikroTik RouterOS
- WinBox
- Laptop/PC
- Kabel Ethernet
- Koneksi internet
