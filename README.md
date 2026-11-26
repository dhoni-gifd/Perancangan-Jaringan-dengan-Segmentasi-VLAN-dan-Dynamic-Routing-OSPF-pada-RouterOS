# Perancangan-Jaringan-dengan-Segmentasi-VLAN-dan-Dynamic-Routing-OSPF-pada-RouterOS

## 🌶️Ringkasan
Proyek ini bertujuan untuk merancang dan membangun simulasi jaringan komputer pada lingkungan perkantoran menggunakan perangkat Cisco. Jaringan dibagi berdasarkan divisi atau departemen perusahaan dengan menerapkan teknologi VLAN (Virtual Local Area Network).

Setiap divisi memiliki jaringan tersendiri untuk meningkatkan keamanan, efisiensi, dan pengelolaan lalu lintas data. Agar setiap divisi tetap dapat berkomunikasi, diterapkan konfigurasi Inter-VLAN Routing menggunakan metode Router-on-a-Stick atau Switch Layer 3.

Selain itu, router difungsikan sebagai DHCP Server untuk memberikan alamat IP secara otomatis kepada komputer klien.

## 🍳Topologi
<img width="785" height="569" alt="topologi project mikrotik" src="https://github.com/user-attachments/assets/14f69ba4-4ce3-40fa-9e6f-41e16d844625" />
" />

## 🥠Media dan Konfigurasi Yang Akan Digunakan

* GNS3
* putty
* router yang terhubung dengan internet dan client
* vlan 10,20,dan 30
* konfigurasi ospf pada setiap router

## 🍕Cara Menguji

1. Buka PC manapun dan verifikasi:
   + IP ditetapkan melalui DHCP
   + Ping dari PC berhasil
2. Lalu di router, verifikasi:
   + Show IP DHCP Binding
   + Show IP Interface Brief

## 🥖Catatan Konfigurasi
| Perangkat | Fitur Utama |
|--------|--------------|
| Switch | Vlan 10, Vlan 20 dan Vlan 30 |
| Router | Router-On-A-Stick dan Server DHCP |
| IP PC | 192.168.10.0/29 (Vlan 10), 192.168.20.0/29 (Vlan 20) dan 192.168.30.0/29 (Vlan 30) |

#

🍜Projek ini dibuat dan diuji oleh Nafisa Maulida Hasan dengan menggunakan Cisco Packet Tracer<3

#

<img width="327" height="320" alt="image" src="https://github.com/user-attachments/assets/1c5558f4-83cd-41f3-87a5-9737d3d30180" />
