Nama    : Awan Abdillah Akbar Dhiya'ulhaq
NRP     : 3121600016
Kelas   : D4 IT A
# Laporan Pratikum Konsep Jaringan
---
## 1.0. Dasar Teori
Dalam transaksi data terdapat layer seperti OSI Layer dan TCP/IP. Model OSI membagi trafik jaringan menjadi beberapa lapisan. Setiap lapisan berdiri sendiri, tidak tergantung pada lapisan yang lain, dan masing-masing membangun berbasis pada jasa layer dibawahnya dan memberikan jasa pada lapisan di atasnya. Berikut adalah catatan singkat ke tujuh lapisan model jaringan OSI:
1. Fisik (mengacu pada media fisik dimana komunikasi terjadi dapat berupa kabel LAN CAT5, sekumpulan kabel fiber optik, gelombang radio, pada dasarnya medium yang dapat digunakan untuk mengirimkan sinyal).
2. Data Link (Pada saat dua atau lebih node berbagi media fisik yang sama, contoh, beberapa komputer tersambung ke sebuah hub, atau sebuah ruangan yang penuh dengan peralatan wireless yang semua menggunakan kanal yang sama, maka mereka akan menggunakan lapisan data link untuk berkomunikasi satu sama lain. Contoh protokol data link yang sering digunakan adalah Ethernet, Token Ring, ATM, dan protokol jaringan wireless (802.11a/b/g)).
3. Jaringan (Lapisan ini adalah lapisan dimana proses routing terjadi. Paket akan meninggalkan sambungan jaringan lokal dan di kirim ulang ke jaringan lain).
4. Transport (Memberikan metoda untuk mencapai jasa tertentu di sebuah node di jaringan. Contoh protokol yang bekerja pada lapisan ini adalah TCP dan UDP).
5. Sesi (Mengatur sesi komunikasi secara logika (virtual) antara aplikasi. NetBIOS dan RPC adalah dua (2) contoh dari protokol di lapisan nomor lima).
6. Presentasi (Berurusan dengan presentasi data, sebelum data mencapai lapisan aplikasi. Pekerjaan di lapisan ini dapat berupa MIME enkoding, kompresi data, pengecekan format, pengurutan byte dsb).
7. Aplikasi (Pada lapisan ini interaksi dengan manusia dilakukan. HTTP, FTP, dan SMTP adalah contoh protokol di lapisan aplikasi).

## 1.1. Media Jaringan Komputer
Pada suatu media jaringan terdapat beberapa jenis yang biasanya digunakan, antara lain kabel tembaga (copper), serat optik (fiber optic) dan jaringan tanpa kabel (wireless) serta kabel LAN. Namun yang paling sering digunakan adalah kabel LAN untuk koneksi jaringan lokal atau lingkup kecil agar terhubung satu sama lain. Terdapat dua jenis kabel LAN yakni STP (Shield Twisted Pair) dan UTP (Unshield Twisted Pair).

## 1.2. Standart Kabel UTP
Pemberian kategori 1/2/3/4/5/5e/6 merupakan kategori spesifikasi untuk masing-masing kabel tembaga dan juga untuk jack. Berikut penjelasan singkat kegunaan setiap kateogri kabel UTP:
| Kabel UTP | Kegunaan |
| --------- | -------- |
| Cat 1 | koneksi suara / sambungan telepon |
| Cat 2 | protocol localtalk (Apple) dengan kecepatan data hingga 4 Mbps |
| Cat 3 | protocol ethernet dengan kecepatan data hingga 10 Mbps |
| Cat 4 | protocol 16 Mbps token ring (IBM) dengan kecepatan data hingga 20 Mbps |
| Cat 5 | protocol fast ethernet dengan kecepatan data hingga 100 Mbps |
| Cat 5e | protocol fast ethernet dengan kecepatan data hingga 250 Mbps |
| Cat 6 | protocol fast ethernet dengan kecepatan data hingga 10 Gbit/s |
## 1.3. Koneksi Dengan Kabel UTP
Dalam menghubungkan jaringan Ethernet dengan menggunakan kabel UTP Category 5, terdapat dua strategi pengabelan, yakni Crossover cable dan Straight-through cable. Kabel Crossover digunakan untuk menghubungkan dua perangkat yang sama (NIC dengan NIC lainnya, hub dengan hub yang lainnya dan lain-lain), sementara kabel Straight-through digunakan untuk menghubungkan NIC dengan hub atau NIC dengan switch.
## 2.0. Pembuatan Kabel UTP
Dalam pembuatan kabel UTP yang merupakan kabel paling sering digunakan untuk menghubungkan sebuah komputer dengan komputer lainnya melalui sebuah perangkat jaringan. Tidak hanya itu, kabel ini juga sering digunakan untuk menghubungkan dari komputer ke perangkat jaringan yang lain seperti router dan switch. Kali ini saya akan membagi tips cara membuat Kabel UTP Straight & Cross untuk bisa membuat jaringan pada komputer agar terhubung secara online ke internet maupun lokal.

## 2.1. Alat Yang Dipersiapkan Dan Kegunakannya
Alat-alat yang perlu dipersiapakan untuk pembuatan kabel UTP:
1. Tank Crimping adalah alat untuk memotong kabel UTP dan untuk menjepit ujung konektor,dan ini sangat penting sekali bagi kita yang ingin belajar cara mengcrimping kabel,alat ini bentuknya hampir sama dengan Tank biasa yang sering kita lihat atau temui.
2. Kabel UTP kita gunakan untuk saling menghubungkan jaringan internet dan di dalam kabel UTP ini terdapat 8 helai kabel kecil yang berwarna-warni.
3. Konektor adalah alat yang kita pasang pada ujung kabel UTP tujuanya agar kabel dapat kita pasang pada port LAN. Konektor RJ-45 harus dipasangkan pada ujung kabel UTP apabila tidak maka Kabel UTP tidak akan berguna.
4. Cable Tester adalah alat untuk menguji hasil crimpingan kabel kita, kalau krimpingan kita salah maka lampu di Cable Tester ini tidak akan menyala dan kalau hasil crimpingan kita sudah benar maka lampu di Cable Tester akan menyala dengan otomatis,jadi alat ini sangat berguna bagi kita untuk mengetahui hasil crimpingan kita.

## 2.2. Langkah Pembuatan Kabel Tipe Straight
Langkah-lankah pembuatan kabel UTP tipe straight
1. Kupas bagian ujung kabel UTP, kira-kira 2 cm.
[![IMG20220823153835.jpg](https://i.postimg.cc/9FPdrP74/IMG20220823153835.jpg)](https://postimg.cc/nCzjWDTZ)
2. Buka pilinan kabel, luruskan dan urutankan kabel sesuai standar gambar.
3. Setelah urutannya sesuai standar, potong dan ratakan ujung kabel,
[![IMG20220823155144.jpg](https://i.postimg.cc/tJQ6g7Rt/IMG20220823155144.jpg)](https://postimg.cc/CB75Phqz)
4. Masukan kabel yang sudah lurus dan sejajar tersebut ke dalam konektor RJ-45, dan pastikan semua kabel posisinya sudah benar sesuai dengan Straight-through.
[![IMG20220823155451.jpg](https://i.postimg.cc/N0Z9NLXq/IMG20220823155451.jpg)](https://postimg.cc/Tyq31dQC)
5. Lakukan crimping menggunakan crimping tools, tekan crimping tool dan pastikan semuapin (kuningan) pada konektor RJ-45 sudah “menggigit” tiap-tiap kabel. biasanya akan terdengar suara “klik”. Setelah selesai pada ujung yang satu, lakukan lagi pada ujung yang lain.


## 2.3. Langkah Pembuatan Kabel Tipe Cross
Langkah-lankah pembuatan kabel UTP tipe Cross
1. Kupas bagian ujung kabel UTP, kira-kira 2 cm.
[![IMG20220823153835.jpg](https://i.postimg.cc/9FPdrP74/IMG20220823153835.jpg)](https://postimg.cc/nCzjWDTZ)
2. Buka pilinan kabel, luruskan dan urutankan kabel sesuai standar gambar.
3. Setelah urutannya sesuai standar, potong dan ratakan ujung kabel,
[![IMG20220823155144.jpg](https://i.postimg.cc/tJQ6g7Rt/IMG20220823155144.jpg)](https://postimg.cc/CB75Phqz)
4. Masukan kabel yang sudah lurus dan sejajar tersebut ke dalam konektor RJ-45, dan pastikan semua kabel posisinya sudah benar sesuai dengan Crossover.
[![IMG20220823155451.jpg](https://i.postimg.cc/N0Z9NLXq/IMG20220823155451.jpg)](https://postimg.cc/Tyq31dQC)
5. Lakukan crimping menggunakan crimping tools, tekan crimping tool dan pastikan semuapin (kuningan) pada konektor RJ-45 sudah “menggigit” tiap-tiap kabel. biasanya akan terdengar suara “klik”. Setelah selesai pada ujung yang satu, lakukan lagi pada ujung yang lain.
---

## 3.0. Pengetesan Kabel UTP
Langkah untuk mengecek kabel yang sudah kita buat tadi yaitu dengan menggunakan LAN tester, caranya masukan masing-masing ujung kabel (konektor RJ-45) ke masing2 port yang tersedia pada LAN tester, nyalakan dan pastikan semua lampu LED menyala sesuai dengan urutan kabel yang kita buat.

## 3.1. Alat Pengetesan
Alat pengetesan pada kabel utp biasanya menggunakan Lan Tester. Lan Tester adalah alat untuk mengecek koneksi sambungan kabel LAN RJ 45 dan RJ 11. Dilengkapi dengan lampu indikator, tombol pengatur kecepatan pengecekan, serta baterai dan kantong kecil. Dari namananya saja sudah jelas bahwa LAN tester adalah alat untuk mengecek sambungan rangkaian kabel LAN RJ 45 dan RJ 11.

## 3.2. Cara Pengetesan Alat 
 Cara Pengetesan kabel croos
   Fungsi kabel Straight adalah digunakan untuk menghubungkan 2 device yang berbeda dan merupakan kabel yang memiliki cara pemasangan yang sama antara ujung satu dengan ujung yang lainnya. Jika kalian mengecek kabel stright, maka lampu no 1 - 8 harus hidup semua secara berurutan.

   -  1 -> 1
   -  2 -> 2
   -  3 -> 3
   -  4 -> 4
   -  5 -> 5
   -  6 -> 6
   -  7 -> 7
   -  8 -> 8
 
   Cara Pengetesal kabel straight
   fungsi kabel Cross adalah digunakan untuk menghubungkan 2 device yang sama, Susunan kabelnya yang berbeda antara ujung satu dengan ujung yang lainnya. Walaupun jenis kombinasi kabelnya berbeda tapi cross menggunakan kabel yang sama yaitu kabel UTP. Dan jika kalian ingin mengecek kabel cross, urutan lampu nya berbeda dengan urutan lampu kabel stright.

   -  1 -> 3
   -  2 -> 6
   -  3 -> 1
   -  4 -> 4
   -  5 -> 5
   -  6 -> 2
   -  7 -> 7
   -  8 -> 8