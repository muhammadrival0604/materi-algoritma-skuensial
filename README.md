# 📘 Materi Ajar: Algoritma Sekuensial dengan Python & Flowgorithm

## 🏫 Informasi Umum
- **Mata Pelajaran**: Dasar-Dasar Pengembangan Perangkat Lunak dan Gim  
- **Elemen**: Pemrograman Terstruktur  
- **Kelas/Fase**: X / Fase E  
- **Model Pembelajaran**: Problem Based Learning (PBL) + Deep Learning  
- **Alokasi Waktu**: 2 JP x 45 menit  
- **Penyusun**: M. Rival Ridautal Lillah, ST  
- **Tahun Pelajaran**: 2025/2026  

---

## 🎯 Capaian & Tujuan Pembelajaran
- **Capaian**: Peserta didik mampu menerapkan prinsip pemrograman terstruktur dengan algoritma sekuensial, memvisualisasikan dengan Flowgorithm, dan mengimplementasikan dengan Python.  
- **Tujuan**:  
  1. Mengidentifikasi konsep algoritma sekuensial.  
  2. Menyusun flowchart dengan Flowgorithm.  
  3. Mengimplementasikan program sekuensial dengan Python.  
  4. Melakukan debugging sederhana pada program.  

---

## 💡 Pertanyaan Pemantik
1. Bagaimana cara menjelaskan aktivitas sehari-hari (misalnya membuat teh) dalam bentuk algoritma sekuensial?  
2. Mengapa Flowgorithm penting sebelum menulis kode Python?  
3. Apa yang terjadi jika urutan algoritma sekuensial tidak sesuai?  
4. Bagaimana cara memastikan program Python sesuai logika algoritma?  

---

## 📘 Materi Pokok

### 1. Konsep Algoritma Sekuensial
- Algoritma = urutan langkah logis untuk menyelesaikan masalah.  
- Sekuensial = setiap langkah dijalankan **berurutan** dari awal sampai akhir tanpa percabangan/perulangan.  

**Contoh kehidupan nyata**:  
1. Ambil gelas  
2. Masukkan teh celup  
3. Tuangkan air panas  
4. Aduk  
5. Minum  

Jika langkah diacak → teh tidak jadi. Sama halnya dengan program.

---

### 2. Flowgorithm
- **Flowgorithm** adalah aplikasi untuk menggambar flowchart.  
- Simbol dasar:  
  - ⭕ **Oval** → Start/End  
  - 🔷 **Jajar Genjang** → Input/Output  
  - 🔲 **Persegi Panjang** → Proses (hitung, operasi)  

**Contoh Flowchart: Menghitung Luas Persegi Panjang**  
![Deskripsi Gambar](https://id-static.z-dn.net/files/d82/29f80e71c1ff72458a040e763dcdddce.png)



---

### 3. Python Dasar

```python
# Program Menghitung Luas Persegi Panjang
panjang = int(input("Masukkan panjang: "))
lebar = int(input("Masukkan lebar: "))

luas = panjang * lebar
print("Luas persegi panjang adalah:", luas)

