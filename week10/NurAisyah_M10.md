# LAPORAN PRAKTIKUM JARKOM MODUL 10 IP

Nama: Nur Aisyah Luhur Pambudi
Kelas: IF-04-02

## 10.2.1 Bagian 1: IPv4 Dasar 
**Langkah-langkah:**
1. Buka Wireshark dan buka file _"ip-ethereal-trace-1.pcap"_.
2. Lakukan penyaringan dengan mengetik "udp || icmp" pada filter.
![Gambar 1](../assets/image/96git.png)
- Terlihat paket ICMP Echo Request, ICMP Time-to-Live Exceeded, dan ICMP Echo Reply yang dihasilkan oleh proses tracert. Host sumber 192.168.1.102 mengirim paket ICMP ke 128.59.23.100 dengan nilai TTL yang meningkat secara bertahap. Ketika TTL mencapai nol pada router tertentu, router tersebut mengirimkan pesan ICMP Time-to-Live Exceeded kembali ke pengirim sehingga jalur yang dilalui paket menuju tujuan dapat diketahui. Selain itu, terdapat beberapa paket UDP seperti SSDP yang merupakan lalu lintas jaringan lokal dan tidak berkaitan langsung dengan traceroute.
