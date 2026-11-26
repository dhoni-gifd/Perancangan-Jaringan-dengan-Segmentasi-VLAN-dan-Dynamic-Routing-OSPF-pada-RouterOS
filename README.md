# Perancangan-Jaringan-dengan-Segmentasi-VLAN-dan-Dynamic-Routing-OSPF-pada-RouterOS

## 🌶️Ringkasan
project Perancangan ini memberikan keamanan berlapis karena trafik antar-segmen melewati router, efisiensi pengelolaan karena rute dipelajari otomatis, serta skalabilitas yang baik ketika jaringan bertambah besar. OSPF dirancang untuk mendukung jaringan berskala besar, sementara VLAN membuat pembagian jaringan tetap fleksibel tanpa mengubah instalasi kabel

## 🍳Topologi
<img width="804" height="586" alt="topologi project 2 mikrotik" src="https://github.com/user-attachments/assets/0af91b96-8d9f-4864-bcbb-a795495b65e1" />

" />

## 🥠Media dan Konfigurasi Yang Akan Digunakan

* GNS3
* putty
* router yang terhubung dengan internet dan client
* vlan siswa,guru,dan TU
* konfigurasi ospf pada setiap router

## 🍕Cara Menguji

1. Buka PC manapun dan verifikasi:
   + IP ditambahkan secara manual
   + Ping sesama vlan
   + ping berbeda vlan
2. Lalu di router, verifikasi:
   + Show IP DHCP Binding
   + Show IP Interface Brief

## 🥖Catatan Konfigurasi
| Perangkat | Fitur Utama |
|--------|--------------|
| cloud | akses internet |
| Router | membuat vlan dan protokol ospf |
| IP PC | 192.168.10.0/30 (Vlan siswa), 192.168.20.0/30 (Vlan guru) dan 192.168.30.0/30 (Vlan TU) |

#

🍜Projek ini dibuat dan diuji oleh Nafisa Maulida Hasan dengan menggunakan Cisco Packet Tracer<3

#

<img width="327" height="320" alt="image" src="https://github.com/user-attachments/assets/1c5558f4-83cd-41f3-87a5-9737d3d30180" />
