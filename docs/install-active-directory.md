# Instalasi Active Directory di Windows Server

## 🧰 Prasyarat
- Windows Server 2019/2022 terinstal
- Akses Administrator
- IP statik disarankan

## 🛠️ Langkah Instalasi

1. Buka **Server Manager**
2. Klik `Add roles and features`
3. Pilih `Role-based or feature-based installation`
4. Pilih server yang ingin dikonfigurasi
5. Centang `Active Directory Domain Services`
6. Klik Next dan Install

## 🔧 Konfigurasi Domain

Setelah instalasi selesai:

1. Klik `Promote this server to a domain controller`
2. Pilih `Add a new forest` dan tentukan nama domain, contoh: `contoso.local`
3. Tentukan password DSRM
4. Ikuti wizard sampai selesai dan restart server
