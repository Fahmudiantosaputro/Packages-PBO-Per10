Proyek ini dibuat untuk memenuhi tugas mata kuliah Pemrograman Berbasis Objek (Java). Pada proyek kali ini dilakukan pembuatan fitur Upload File CSV menggunakan Java GUI (NetBeans) yang terhubung dengan database MySQL.

Dengan adanya tombol Upload, data dapat dimasukkan ke tabel database secara otomatis hanya dengan memilih file CSV yang berisi data mahasiswa.

Fitur ini dirancang agar pengguna tidak perlu melakukan input data secara manual ke dalam database, sehingga proses pengolahan data menjadi lebih cepat, efisien, dan meminimalkan kesalahan. Implementasi program mencakup:
-	Pembuatan GUI (Graphical User Interface): Mendesain antarmuka dengan Java Swing yang memiliki tombol Upload dan area notifikasi.
-	Penggunaan JFileChooser: Menyediakan dialog pemilihan file CSV dari komputer pengguna.
-	Pembacaan File CSV: Menggunakan kelas BufferedReader untuk membaca isi file baris per baris.-	Koneksi ke Database MySQL: Menghubungkan aplikasi dengan database untuk melakukan penyimpanan data.
-	Eksekusi Query dengan PreparedStatement: Memasukkan data ke tabel MySQL secara otomatis sesuai isi file CSV.
-	Pengujian Program: Melakukan uji coba proses upload untuk memastikan data terbaca dan tersimpan dengan benar.
2.	Tujuan
-	Memahami proses pembuatan fitur upload file CSV pada Java GUI.
-	Mempelajari penggunaan JFileChooser untuk memilih file dari sistem lokal PC.
-	Menguasai teknik pembacaan file menggunakan BufferedReader.
-	Mengetahui cara menghubungkan Java dengan database MySQL.
-	Melatih penggunaan PreparedStatement untuk memasukkan data ke dalam tabel secara otomatis.
-	Mengembangkan kemampuan membuat aplikasi desktop sederhana yang interaktif dan terintegrasi dengan database.
-	
  Implementasi Fitur Upload Data CSV ke Database MySQL Menggunakan Java GUI di NetBeans.
 	1.	Langkah pertama, menambahkan bottom upload data csv bertujuan untuk mengimplementasikan penambahan file data secara otomatis menggunakan java GUI di NetBeans.
<img width="917" height="423" alt="image" src="https://github.com/user-attachments/assets/55448ca1-0057-495a-8d12-eb3320983456" />
2.	Langkah kedua, menambahkan keyword atau code update bertujuan untuk menghubungkan bottom update ke table database.
   <img width="876" height="486" alt="image" src="https://github.com/user-attachments/assets/31d2a47f-39a9-4912-9679-466c6fc194e1" />
<img width="871" height="580" alt="image" src="https://github.com/user-attachments/assets/7be7db78-8cba-4bdf-a7d9-81cc3dce059e" />
<img width="880" height="564" alt="image" src="https://github.com/user-attachments/assets/49c49385-860c-4ce9-8fb9-62431e15d60f" />
<img width="869" height="379" alt="image" src="https://github.com/user-attachments/assets/4596e3e4-2879-4f0b-a99a-f1335139e488" />
3.	Langkah ketiga, membuat data dinote atau di excel dengan urutan sesuai nama tabel didatabase teman-teman. Titik koma nya sesuaikan diversi
    laptop teman teman Ketika masih salah berarti ada 2 versi yaitu dari titik komanya diganti dengan titik aja atau mungkin dari code bottom
  	updatenya tidak bisa menginput. Setelah itu save notenya dengan format namanote.csv.
<img width="856" height="459" alt="image" src="https://github.com/user-attachments/assets/7d1cbf5f-4e28-4231-9659-7c8c34d11c40" />
<img width="857" height="482" alt="image" src="https://github.com/user-attachments/assets/ebc2f24e-7e95-48d9-86b8-22f054fb6c87" />
4.	Langkah ke empat, Buka Program Netbeans yang dibuat lalu, run program dan klik bottom update, mencari nama file sesuai tempat file berada dimana.
   Klik open maka data akan bertambah secara otomatis sesuai data yang di tambahkan dinote teman-teman.
<img width="860" height="484" alt="image" src="https://github.com/user-attachments/assets/67267084-cf40-4cba-a5de-edd328e5dde7" />
<img width="870" height="489" alt="image" src="https://github.com/user-attachments/assets/f1e6b183-48f5-4cc7-be59-f608a97c5c81" />
<img width="870" height="489" alt="image" src="https://github.com/user-attachments/assets/04dcbe29-6821-488a-bdf7-d922aed2f909" />
5.	Output terakhir yang ditampilakan.
   <img width="886" height="498" alt="image" src="https://github.com/user-attachments/assets/93141a47-342f-4824-bf4e-4026b388e2c2" />
   <img width="890" height="500" alt="image" src="https://github.com/user-attachments/assets/4ccc7671-2469-4811-94d4-462f748188b3" />










