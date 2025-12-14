# Tugas-Pemrograman-Pertemuan-13

# Nama : Sabrina Dwi Ajeng <br>
# Nim  : 312510308 <br>
# Kelas: TI.25 C5

# Latihan 1: Kalkulator Aman

Deskripsi

Membuat program kalkulator sederhana yang meminta dua angka dan satu operator (+, -, *, /) dari pengguna. Program ini harus dilengkapi dengan penanganan exception untuk memastikan keamanannya.

Implementasi Penanganan Exception

try-except (ValueError): Digunakan untuk menangani kasus di mana pengguna memasukkan input yang bukan angka (misalnya, teks).

try-except (ZeroDivisionError): Digunakan untuk menangani pembagian dengan nol.

raise Exception: Digunakan untuk memunculkan pesan kesalahan kustom jika operator yang dimasukkan tidak valid (misalnya, ^).

Contoh Hasil

--- Kalkulator Aman ---
Masukkan operator (+, -, *, /): /
Masukkan angka pertama: 10
Masukkan angka kedua: 0

[ERROR] Pembagian dengan nol tidak diperbolehkan.
-----------------------

# Latihan 2: Validasi Daftar Nilai

Deskripsi

Diberikan sebuah list nilai mahasiswa yang bercampur antara angka dan karakter non-angka (nilai = [80, 90, 'A', 70, 100, 'B']). Buat program yang mengiterasi list tersebut untuk menghitung rata-rata nilai dari data yang valid saja.

Implementasi Penanganan Exception

Digunakan blok try-except di dalam loop (iterasi) untuk mencoba mengkonversi setiap elemen menjadi angka.

Jika terjadi ValueError (karena elemen berupa string seperti 'A' atau 'B'), exception ditangkap dan program melanjutkan (continue) ke elemen berikutnya tanpa menghentikan program.

Contoh Hasil

--- Validasi Daftar Nilai ---
List Nilai Awal: [80, 90, 'A', 70, 100, 'B']
-----------------------------

Nilai Valid diproses: 80.0
Nilai Valid diproses: 90.0
Data Non-Angka dilewati: 'A'
Nilai Valid diproses: 70.0
Nilai Valid diproses: 100.0
Data Non-Angka dilewati: 'B'

List nilai yang diproses: 4 item
Total Nilai Valid: 340.0
Rata-rata dari data valid: 85.00
Apakah Anda ingin saya menambahkan bagian tentang cara menjalankan kode (How to Run) atau informasi lisensi (License) pada README ini?
