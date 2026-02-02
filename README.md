# modern-hotel-network

Project Hotel Modern
<img width="1562" height="670" alt="Image" src="https://github.com/user-attachments/assets/115d65a3-cbe4-403e-ad65-c0bd7cdcd3e2" />

## Deskripsi Proyek

Proyek Hotel Modern ini merupakan simulasi jaringan komputer menggunakan Cisco Packet Tracer
yang dirancang untuk mendukung kebutuhan operasional hotel bertingkat. Jaringan dibagi ke dalam
beberapa VLAN berdasarkan fungsi dan lantai guna meningkatkan efisiensi, keamanan, dan
kemudahan manajemen jaringan.

Arsitektur jaringan menggunakan tiga router yang saling terhubung antar lantai, yaitu lantai 1,
lantai 2, dan lantai 3. Protokol routing dinamis OSPF digunakan untuk memungkinkan pertukaran
informasi routing secara otomatis antar router, sehingga seluruh jaringan dapat saling
terhubung tanpa konfigurasi routing statis.

Layanan DHCP diterapkan pada masing-masing router untuk memberikan alamat IP secara otomatis
kepada perangkat jaringan seperti PC, laptop, smartphone, dan printer. Dengan DHCP, proses
konfigurasi jaringan menjadi lebih sederhana dan meminimalkan kesalahan pengaturan IP secara
manual.

Setiap VLAN merepresentasikan unit kerja yang berbeda, seperti Admin, Reception, Sales, HR,
Finance, Logistics, dan Store. Segmentasi jaringan ini bertujuan untuk mengurangi broadcast
traffic serta meningkatkan keamanan komunikasi data antar unit.

Dengan penerapan OSPF dan DHCP, jaringan hotel modern ini mampu memberikan konektivitas yang
andal, terstruktur, dan mudah dikembangkan sesuai dengan kebutuhan operasional hotel.

## Protokol yang Digunakan

OSPF (Open Shortest Path First) merupakan protokol routing dinamis yang digunakan untuk
menentukan jalur terbaik antar router berdasarkan cost. OSPF memungkinkan jaringan
beradaptasi secara otomatis terhadap perubahan topologi.

DHCP (Dynamic Host Configuration Protocol) digunakan untuk mendistribusikan alamat IP,
gateway, dan DNS secara otomatis kepada perangkat klien, sehingga mempermudah pengelolaan
jaringan dan mengurangi kesalahan konfigurasi.

## Tujuan Proyek
- Menerapkan konsep VLAN dan subnetting pada jaringan hotel
- Mengimplementasikan routing dinamis menggunakan OSPF
- Mengelola distribusi IP address menggunakan DHCP
- Mensimulasikan jaringan bertingkat yang terstruktur dan efisien
