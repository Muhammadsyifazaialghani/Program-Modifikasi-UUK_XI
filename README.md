# Program-Modifikasi-UUK_XI

##Penggunaan Program
NOTE: Codingan Menggunakan Programiz dari Notepad.

##Melakukan Input Data
(Bagian Header dan Deklarasi Fungsi)
<img width="187" alt="image" src="https://github.com/user-attachments/assets/ddf32827-7853-4b87-9c71-8cfe62e36685">
<img width="334" alt="image" src="https://github.com/user-attachments/assets/a28ed320-c8cf-46a6-856e-00038fcbfa83">

- #include <iostream>: Ini adalah direktif preprocessor yang digunakan untuk memasukkan pustaka input/output standar di C++.
- using namespace std;: Ini digunakan agar kita tidak perlu menulis std:: sebelum penggunaan objek dalam pustaka standar seperti cout dan endl.
- Deklarasi fungsi: Tiga fungsi dideklarasikan di sini (cariNilaiTertinggi, cariNilaiTerendah, dan hitungRataRata) yang akan digunakan di dalam program untuk mencari nilai tertinggi, nilai terendah, dan menghitung rata-rata.
  
(Fungsi Main)
<img width="441" alt="image" src="https://github.com/user-attachments/assets/e618e1c9-f2c0-44bd-913f-54e595a38397">
<img width="439" alt="image" src="https://github.com/user-attachments/assets/3b277db0-abf9-42ce-b17b-91504128edc1">

- int main(): Fungsi main adalah titik masuk utama program C++.
- int nilai[11] = {76, 85, 90, 93, 82, 75, 80, 90, 95, 85, 93};: Inisialisasi array nilai dengan 11 nilai.
- cout << "Nilai Matematika Siswa: " << endl;: Mencetak judul.
- for (int i = 0; i < 11; ++i) { ... }: Loop ini mencetak setiap nilai dalam array nilai.
- int nilaiTertinggi = cariNilaiTertinggi(nilai, 11);: Memanggil fungsi cariNilaiTertinggi untuk menemukan nilai tertinggi dalam array nilai.
- int nilaiTerendah = cariNilaiTerendah(nilai, 11);: Memanggil fungsi cariNilaiTerendah untuk menemukan nilai terendah dalam array nilai.
- float rataRata = hitungRataRata(nilai, 11);: Memanggil fungsi hitungRataRata untuk menghitung rata-rata nilai dalam array nilai.
- cout statements berikutnya mencetak nilai tertinggi, terendah, dan rata-rata.

(Fungsi Cari Nilai Tertinggi)
<img width="448" alt="image" src="https://github.com/user-attachments/assets/456f5509-b7b4-4b13-8922-2299dc967696">

- int cariNilaiTertinggi(int nilai[], int n): Fungsi ini menerima array nilai dan jumlah elemen n.
- int max = nilai[0];: Menginisialisasi max dengan elemen pertama array.
- for (int i = 1; i < n; ++i) { ... }: Loop untuk membandingkan setiap elemen array dengan max.
- if (nilai[i] > max) { max = nilai[i]; }: Jika elemen saat ini lebih besar dari max, perbarui max.
- return max;: Mengembalikan nilai tertinggi.

(Fungsi Cari Nilai Terendah)
<img width="450" alt="image" src="https://github.com/user-attachments/assets/d884999c-ec6e-4017-99ff-e70c086c1369">

- int cariNilaiTerendah(int nilai[], int n): Fungsi ini menerima array nilai dan jumlah elemen n.
- int min = nilai[0];: Menginisialisasi min dengan elemen pertama array.
- for (int i = 1; i < n; ++i) { ... }: Loop untuk membandingkan setiap elemen array dengan min.
- if (nilai[i] < min) { min = nilai[i]; }: Jika elemen saat ini lebih kecil dari min, perbarui min.
- return min;: Mengembalikan nilai terendah.

(Fungsi Hitung Rata-rata)
<img width="443" alt="image" src="https://github.com/user-attachments/assets/ac3b6469-e59c-45b8-8ca7-951cb2373a71">
- float hitungRataRata(int nilai[], int n): Fungsi ini menerima array nilai dan jumlah elemen n.
- int total = 0;: Menginisialisasi total dengan 0.
- for (int i = 0; i < n; ++i) { ... }: Loop untuk menjumlahkan semua elemen dalam array.
- total += nilai[i];: Menambahkan setiap elemen ke total.
- return static_cast<float>(total) / n;: Mengembalikan rata-rata dengan membagi total dengan jumlah elemen n.


##Tampilan Akhir
<img width="461" alt="image" src="https://github.com/user-attachments/assets/f8c83039-d3ab-4eba-8aca-3f91da81c09e">














