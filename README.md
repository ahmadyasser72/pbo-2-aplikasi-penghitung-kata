# Tugas 5 - Aplikasi Penghitung Kata ([screenshot](#screenshot))

Aplikasi ini memungkinkan pengguna untuk menghitung jumlah kata, karakter, kalimat, dan paragraf dalam teks yang dimasukkan. Selain itu, pengguna juga dapat mencari kata dalam teks dan menyimpan teks beserta hasil perhitungan ke dalam file teks.

## Fitur Aplikasi

- **Jumlah Kata**  
  Menghitung jumlah kata dalam teks yang dimasukkan.

- **Jumlah Karakter**  
  Menghitung jumlah karakter dalam teks yang dimasukkan.

- **Jumlah Kalimat**  
  Menghitung jumlah kalimat dalam teks menggunakan pemisah kalimat.

- **Jumlah Paragraf**  
  Menghitung jumlah paragraf dalam teks yang dipisahkan oleh dua baris kosong.

- **Cari Kata**  
  Mencari kata tertentu dalam teks dan menyorotnya.

- **Simpan ke File**  
  Menyimpan teks beserta hasil perhitungan ke dalam file teks.

## Cara Menjalankan Aplikasi

### 1. **Instalasi Dependensi**

Aplikasi ini tidak membutuhkan dependensi eksternal khusus selain Java SE. Pastikan Anda telah menginstal JDK yang kompatibel (Java 8 atau lebih tinggi).

### 2. **Langkah Menjalankan**

- Buka project ini di IDE seperti **NetBeans**.
- Klik tombol **Run** untuk menjalankan aplikasi.

### 3. **Interaksi dengan Aplikasi**

- Masukkan teks di area input.
- Klik **Hitung** untuk menghitung jumlah kata, karakter, kalimat, dan paragraf.
- Gunakan fitur **Cari** untuk mencari kata dalam teks.
- Klik **Simpan** untuk menyimpan teks dan hasil perhitungan ke dalam file teks.

## Desain GUI

Aplikasi ini memiliki tampilan antarmuka yang terdiri dari:

- **Text Area (jTextArea1)**: Untuk memasukkan teks.
- **Button (Hitung)**: Untuk menghitung jumlah kata, karakter, kalimat, dan paragraf.
- **Label**: Untuk menampilkan hasil perhitungan jumlah kata, karakter, kalimat, dan paragraf.
- **Text Field (jTextFieldCari)**: Untuk mencari kata dalam teks.
- **Button (Cari)**: Untuk mencari kata yang dimasukkan pada text field.
- **Button (Simpan)**: Untuk menyimpan teks beserta hasil perhitungan ke file.

## Penjelasan Fitur

1. **Jumlah Kata**  
   Menghitung dan menampilkan jumlah kata dalam teks yang dimasukkan.

2. **Jumlah Karakter**  
   Menghitung dan menampilkan jumlah karakter dalam teks.

3. **Jumlah Kalimat**  
   Menghitung dan menampilkan jumlah kalimat dalam teks berdasarkan pemisahan kalimat.

4. **Jumlah Paragraf**  
   Menghitung dan menampilkan jumlah paragraf dalam teks.

5. **Cari Kata**  
   Mencari dan menyorot kata yang dicari dalam teks.

6. **Simpan ke File**  
   Menyimpan teks dan hasil perhitungan ke dalam file teks dengan ekstensi `.txt`.

## Detail tugas

1. Deskripsi Program:

   - Gunakan JTextArea dalam JScrollPane untuk input teks
   - Setelah menekan tombol Hitung, hasil perhitungan berupa jumlahkata dan karakter ditampilkan pada beberapa JLabel

2. Komponen GUI: JFrame, JPanel, JLabel, JTextArea, JScrollPane, JButton

3. Logika Program: Manipulasi string, Ekspresi reguler

4. Events:

   - ActionListener untuk tombol Hitung
   - DocumentListener pada JTextArea untuk menghitung secara real-time

5. Variasi:

   - Tambahkan fitur untuk menghitung jumlah kalimat dan paragraf
   - Implementasikan fungsi pencarian kata tertentu dalam teks
   - Sediakan opsi untuk menyimpan teks dan hasil perhitungan ke file

## Screenshot

Nama : Ahmad Yasser

NPM  : 2210010525

Kelas: 5A REGULER BJB TI

1. Tampilan awal
![image](https://github.com/user-attachments/assets/7f46a03e-0603-49b7-92aa-8f61ea81ef78)

2. Input teks

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sit amet leo eget magna malesuada accumsan. Mauris eget aliquet libero, quis sodales turpis. Aliquam erat volutpat. Aliquam efficitur felis vitae urna auctor, sed vehicula velit faucibus. Phasellus finibus, ipsum ut consequat porta, risus tortor tristique elit, ut congue enim risus id lectus. Vivamus condimentum quis eros id aliquet. Morbi rhoncus eu nunc vel aliquam. In posuere nisi sed ex euismod sagittis.

Ut arcu justo, ullamcorper at ullamcorper ut, mattis quis nibh. Donec dapibus nunc vel lorem fermentum, non commodo augue volutpat. Vestibulum fringilla sed nulla id maximus. Suspendisse potenti. Sed eleifend neque sed purus cursus fringilla. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Duis non felis mattis, interdum nunc non, venenatis turpis. Phasellus tincidunt laoreet varius. Nullam vulputate aliquam mi ac finibus. Etiam consectetur turpis vel metus convallis commodo. Maecenas interdum magna eu dui convallis, vel vestibulum odio semper. 
```
![image](https://github.com/user-attachments/assets/40d2b089-27d7-4835-9f17-ab2a7350e27c)

3. Cari kata ipsum
![image](https://github.com/user-attachments/assets/8f9ec1b5-42f5-4876-9e44-af223464f222)

4. Cari kata ipsum lagi
![image](https://github.com/user-attachments/assets/d9abbcb2-650f-4ef1-8b45-4ce3acd6e338)

5. Cari kata yang tidak ditemukan
![image](https://github.com/user-attachments/assets/79aee65f-d93e-46c3-b2c0-71b222c83e4f)

6. Hasil simpan
![image](https://github.com/user-attachments/assets/97f3ecfa-ee81-451e-b85d-6084ed8e51d4)
![image](https://github.com/user-attachments/assets/aa6066fd-1863-4662-b26c-c9623ace1332)

