# Aplikasi Konversi Suhu

## Biodata Pembuat
- **Nama**: Nabila Parastiwi
- **NPM**: 2210010420
- **Kelas**: Reguler 5A Pagi Banjarmasin
- **Mata Kuliah**: Pemrograman Berbasis Objek 2
- **Jurusan**: Teknik Informatika - TI
- **Fakultas**: Teknologi Informatika
- **Kampus**: Universitas Islam Kalimantan Muhammad Arsyad Al-Banjari

## Deskripsi Proyek
Aplikasi ini merupakan proyek Pemrograman Berbasis Objek 2 yang dikembangkan menggunakan Java dengan NetBeans IDE dan Swing untuk GUI. Aplikasi ini memungkinkan pengguna untuk mengonversi suhu dari satu satuan ke satuan lainnya, seperti dari Celcius ke Fahrenheit, Reamur, dan Kelvin. Konversi dilakukan otomatis setiap kali pengguna memasukkan nilai, dan aplikasi hanya menerima input angka.

## Fitur
- Input suhu yang hanya menerima angka dan titik desimal
- Pemilihan satuan suhu awal menggunakan `JComboBox`
- Pemilihan satuan suhu tujuan menggunakan `JRadioButton`
- Konversi otomatis saat nilai input berubah menggunakan `DocumentListener`
- Penggunaan `ButtonGroup` untuk memastikan hanya satu `JRadioButton` yang bisa dipilih
- Tampilan hasil konversi secara langsung

## Teknologi yang Digunakan
- Java
- NetBeans IDE
- Swing untuk GUI

## Struktur Program
1. **Deskripsi Program**:
   - Pengguna memasukkan nilai suhu dan memilih jenis konversi
   - Hasil konversi ditampilkan setelah input diubah

2. **Komponen GUI**:
   - JFrame, JPanel, JLabel, JTextField, JComboBox, JButton, JRadioButton

3. **Logika Program**:
   - Rumus konversi suhu sesuai dengan satuan yang dipilih
   - Validasi input hanya menerima angka dan titik desimal

4. **Events**:
   - ActionListener untuk tombol Konversi
   - DocumentListener untuk konversi otomatis saat input berubah
   - KeyAdapter pada JTextField untuk membatasi input hanya angka dan titik desimal

5. **Variasi**:
   - Implementasi otomatis konversi saat input berubah
   - Skala suhu tambahan seperti Reamur dan Kelvin

## Cara Menggunakan
1. Masukkan nilai suhu pada `JTextField`.
2. Pilih satuan suhu awal pada `JComboBox`.
3. Pilih satuan suhu tujuan pada `JRadioButton`.
4. Hasil konversi akan tampil secara otomatis di bawah input.
