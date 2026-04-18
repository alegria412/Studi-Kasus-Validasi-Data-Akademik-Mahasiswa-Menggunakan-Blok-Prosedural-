🎓 Sistem Validasi Data Akademik Mahasiswa dan Kelayakan KRS Berbasis MySQL

📌 Deskripsi

Project ini adalah implementasi Stored Procedure di MySQL untuk memvalidasi data akademik mahasiswa dan menentukan apakah mahasiswa layak mengisi KRS (Kartu Rencana Studi).

Program akan memproses beberapa data penting seperti:

-Status pembayaran
-Jumlah SKS yang diambil
-Indeks Prestasi Kumulatif (IPK)

Hasilnya ditampilkan dalam bentuk informasi yang jelas, terstruktur, dan mudah dipahami.

🎯 Tujuan

Project ini dibuat untuk:

-Memahami konsep Stored Procedure di MySQL
-Menggunakan variabel dan konstanta dalam database
-Menerapkan logika percabangan (IF-ELSE)
-Mengolah data menjadi output yang informatif

⚙️ Teknologi yang Digunakan
MySQL
-SQL (Stored Procedure)
-phpMyAdmin (opsional)

🧠 Konsep yang Digunakan

Program ini mengimplementasikan beberapa konsep dalam pemrograman basis data, yaitu:

Stored Procedure untuk membungkus logika program
Variabel untuk menyimpan data sementara
Konstanta untuk nilai tetap
Percabangan (IF-ELSE) untuk pengambilan keputusan
Operator logika (AND, OR) untuk kombinasi kondisi
CONCAT untuk menggabungkan output

📂 Struktur Program

🔹 Bagian A – Identitas Mahasiswa

Menampilkan informasi dasar mahasiswa yang meliputi nama, NIM, semester, program studi, dan kampus.

🔹 Bagian B – Validasi Data Akademik

Melakukan validasi terhadap:

Status pembayaran
Jumlah SKS
Semester

Output yang dihasilkan:

Status data (Valid / Tidak Valid)
Kategori beban studi
Performa akademik berdasarkan IPK
🔹 Bagian C – Penentuan Kelayakan KRS

Menentukan apakah mahasiswa:

LAYAK atau
TIDAK LAYAK

Program juga memberikan:

Kategori beban studi
Performa akademik
Alasan keputusan
🔹 Bagian D – Perbandingan Mahasiswa

Membandingkan dua mahasiswa berdasarkan:

IPK sebagai indikator utama
SKS sebagai indikator tambahan

Output berupa kesimpulan mahasiswa yang lebih unggul.

📊 Hasil Program

Program mampu:

Menampilkan identitas mahasiswa secara lengkap
Melakukan validasi data akademik
Menentukan kelayakan pengisian KRS
Membandingkan performa akademik mahasiswa
🧠 Analisis

Berdasarkan hasil pengujian, program telah berjalan sesuai dengan logika yang dirancang. Setiap bagian mampu menghasilkan output yang berbeda sesuai dengan kondisi input yang diberikan.

Penggunaan struktur percabangan dan variabel membuat program lebih fleksibel dan mudah dikembangkan.

📝 Kesimpulan

Program ini berhasil mengimplementasikan konsep blok prosedural dalam MySQL untuk menyelesaikan studi kasus validasi data akademik mahasiswa.

Selain itu, program juga mampu:

Mengolah data secara sistematis
Menghasilkan keputusan yang logis
Menyajikan informasi yang jelas dan informatif

Dengan demikian, praktikum ini dapat meningkatkan pemahaman terhadap pemrograman basis data serta kemampuan dalam menyusun logika program.
