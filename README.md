
# Perhitungan Diskon

**Tugas Pemrograman GUI**  
Nama: Atma Fathul Hadi  
NPM: 2210010425  

## 1. Deskripsi Program:
Program ini adalah aplikasi GUI untuk menghitung diskon harga barang. Pengguna memasukkan harga asli, memilih persentase diskon melalui slider atau combo box, dan dapat memasukkan kode kupon untuk tambahan diskon. Program kemudian menampilkan harga akhir setelah diskon dan penghematan yang didapatkan.

## 2. Komponen GUI:
Program ini dibuat menggunakan komponen GUI berikut:
- **JFrame**: Untuk kerangka utama aplikasi
- **JPanel**: Sebagai wadah komponen GUI
- **JLabel**: Untuk label teks seperti "Harga" dan "Kode Diskon"
- **JTextField**: Untuk memasukkan harga asli dan kode diskon
- **JComboBox**: Untuk memilih persentase diskon
- **JSlider**: Sebagai alternatif untuk memilih persentase diskon
- **JButton**: Untuk tombol "Hitung" dan "Keluar"
- **JTextArea**: Untuk menampilkan riwayat perhitungan diskon

## 3. Logika Program:
Program ini melakukan perhitungan diskon menggunakan aritmatika dasar. Setelah pengguna memasukkan harga asli dan memilih diskon, aplikasi menghitung harga akhir dan penghematan, kemudian menampilkan hasilnya. Jika pengguna memasukkan kode kupon yang valid ("DISKON10"), diskon tambahan 10% diterapkan.

## 4. Events:
- **ActionListener pada tombol Hitung**: Melakukan perhitungan diskon ketika tombol ditekan
- **ActionListener pada tombol Keluar**: Menutup program ketika tombol ditekan
- **ChangeListener pada JSlider**: Menampilkan persentase diskon saat slider digeser
- **ItemListener pada JComboBox**: Memperbarui slider saat persentase dipilih

## 5. Variasi Program:
- **Kode Kupon**: Pengguna dapat memasukkan kode kupon untuk diskon tambahan.
- **JSlider untuk Persentase Diskon**: Slider memberikan alternatif untuk memilih diskon dalam bentuk persen.
- **Riwayat Perhitungan**: Semua perhitungan yang dilakukan ditampilkan dalam JTextArea untuk riwayat.

## Hasil Program:
Program akan menampilkan harga akhir, penghematan yang didapatkan, dan mencatat riwayat diskon yang telah dilakukan dalam JTextArea.

## Indikator Penilaian:

| No  | Komponen         |  Persentase  |
| :-: | ---------------- |   :-----:    |
|  1  | Komponen GUI     |    20%       |
|  2  | Logika Program   |    20%       |
|  3  | Kesesuaian UI    |    15%       |
|  4  | Constructor      |    15%       |
|  5  | Memenuhi Variasi |    30%       |
|     | **TOTAL**        | 100%         |

## Cara Menjalankan Program:
1. Buka program di lingkungan Java IDE seperti NetBeans atau Eclipse.
2. Jalankan program dan masukkan harga asli pada kolom "Harga".
3. Pilih persentase diskon melalui combo box atau slider.
4. Jika memiliki kode kupon, masukkan di kolom "Kode Diskon".
5. Tekan tombol "Hitung" untuk mendapatkan harga akhir dan penghematan.
6. Riwayat perhitungan diskon akan ditampilkan di area riwayat.
7. Tekan tombol "Keluar" untuk menutup aplikasi.

---
