# Praktikum 2 Putri Melati R
# 1). Buat codingan dari Flowchart yang menentukan bilangan terbesar dari 3 bilangan yang diinputkan 

![1  codingan 3 bilangan](https://github.com/user-attachments/assets/8e12eb17-1b3e-4bb2-a107-75050c85a356)

1. Input Bilangan:
   
   Masukkan tiga bilangan. Fungsi input() digunakan untuk mengambil input dari pengguna, dan float() digunakan untuk mengonversi input tersebut menjadi tipe data float.
   
3. Pengecekan Bilangan Terbesar:
   
   Kemudian menggunakan struktur kontrol if, elif, dan else untuk membandingkan ketiga bilangan:
   
      Jika a lebih besar dari b dan c, maka a adalah bilangan terbesar.
   
      Jika b lebih besar dari a dan c, maka b adalah bilangan terbesar.
   
      Jika tidak ada kondisi di atas yang terpenuhi, maka c dianggap sebagai bilangan terbesar.
   
![1  Run codingan 3 bilangan](https://github.com/user-attachments/assets/9f03291b-bf67-4a1e-a712-139c6b27640d)

Berdasarkan input:

A (28) tidak lebih besar dari C (2005).

B (10) tidak lebih besar dari C (2005).

Oleh karena itu, C (2005) adalah bilangan terbesar di antara ketiga bilangan yang diinputkan.

Output yang dihasilkan, yaitu "(c) adalah bilangan terbesar", adalah hasil yang benar dan sesuai dengan logika yang diterapkan dalam kode tersebut. Program berhasil mengidentifikasi bilangan terbesar dari ketiga bilangan yang diberikan.

Flowchart:

![WhatsApp Image 2024-10-27 at 08 27 40_625fd02e](https://github.com/user-attachments/assets/6e209b2d-f0a7-4f4d-bebd-6b4d72aee6f0)

# 2.) Buat codingan dari flowchart yang menentukan bilangan terbesar dari N bilangan yang diinputkan. untuk menentukan jumlah N, berikan masukkan angka 0

![2 codingan](https://github.com/user-attachments/assets/5e42bc30-dc4b-4102-9ebc-4b7b4006607a)

1. Inisialisasi Variabel:
   
   Menginisialisasi variabel terbesar dengan nilai negatif tak terhingga (-inf). Ini dilakukan agar setiap bilangan yang dimasukkan ke dalam fungsi dapat dibandingkan dan, jika lebih besar, akan menggantikan        nilai terbesar.
   
2. Input Jumlah Bilangan:
   
   Masukkan jumlah bilangan yang ingin dimasukkan. Jika pengguna memasukkan 0, maka fungsi akan berhenti dan tidak ada bilangan yang akan diproses.

3. Pengecekan Input Awal:

   Jika pengguna memasukkan 0, maka fungsi akan mencetak pesan bahwa tidak ada bilangan yang dimasukkan dan mengakhiri eksekusi fungsi dengan return.

4. Perumusan dan Perbandingan:

   Di dalam loop for, fungsi meminta pengguna untuk memasukkan n bilangan satu per satu. Setiap bilangan yang dimasukkan akan dibandingkan dengan nilai terbesar. Jika bilangan yang dimasukkan lebih besar dari       terbesar, maka nilai terbesar akan diperbarui dengan bilangan yang baru dimasukkan.

5. Setelah loop selesai, fungsi akan mencetak bilangan terbesar yang ditemukan selama proses input.

6. fungsi cari_terbesar_dari_n() dipanggil untuk menjalankan semua proses yang telah dijelaskan.
   
![2  run codingan](https://github.com/user-attachments/assets/e5672e8b-446b-4776-b168-dae2f075af1b)

Hasil Output: Setelah semua bilangan dimasukkan (5, 3, 10, 0, 7). Nilai terbesar adalah 10, dan karena bilangan yang dimasukkan adalah tipe float, maka hasilnya ditampilkan sebagai 10.0.

Flowchart:

![WhatsApp Image 2024-10-27 at 08 27 21_dcfb6118](https://github.com/user-attachments/assets/c130d888-78de-4bc9-94f1-2164d43353dd)


