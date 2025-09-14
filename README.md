# Algoritma Sekuensial

Algoritma sekuensial adalah jenis algoritma yang langkah-langkahnya dieksekusi satu demi satu dalam urutan linier.  
Setiap langkah bergantung pada penyelesaian langkah sebelumnya, memastikan proses mengalir secara logis dari awal hingga akhir tanpa eksekusi paralel.

---

## Karakteristik Algoritma Sekuensial
1. **Eksekusi Linier**  
   Langkah-langkah dilakukan satu per satu dalam urutan yang telah ditetapkan.  
2. **Deterministik**  
   Urutan operasinya tetap, menghasilkan hasil yang dapat diprediksi.  
3. **Utas Tunggal Eksekusi**  
   Hanya satu tugas yang diproses pada satu waktu.  
4. **Kesederhanaan**  
   Mudah dipahami dan diterapkan.  

---

## Langkah-Langkah dalam Algoritma Sekuensial
1. **Awal** – Tentukan titik awal proses.  
2. **Masukan** – Kumpulkan data yang dibutuhkan.  
3. **Pengolahan** – Lakukan operasi/perhitungan secara berurutan.  
4. **Keluaran** – Tampilkan atau simpan hasil.  
5. **Akhir** – Hentikan proses.  

---

## Contoh Algoritma Sekuensial
**Soal:** Hitung luas persegi panjang.  

1. Awal  
2. Masukkan panjang (P) dan lebar (L).  
3. Hitung luas: `Luas = P × L`.  
4. Keluarkan hasil luas.  
5. Akhir  

---

## Pseudocode
```

Awal
Masukan P, L
Luas = P \* L
Keluaran Luas
Akhir

```

---

## Representasi Diagram Alir

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1aloT2Lp-ZuNe4yKrm92ltPabLiUTypkN" 
       alt="Flowchart Algoritma Sekuensial" width="400"/>
</p>





---

## Contoh Program Python
```python
# Program menghitung luas persegi panjang

p = int(input("Masukkan panjang: "))
l = int(input("Masukkan lebar: "))

luas = p * l

print("Luas persegi panjang =", luas)
````

---

## Aplikasi Algoritma Sekuensial

1. **Perhitungan Matematika Sederhana** – penambahan, pengurangan, perkalian.
2. **Pengolahan Data** – mengurutkan atau menyaring data langkah demi langkah.
3. **Otomatisasi** – tugas berurutan seperti pengisian formulir atau entri data.

---

## Keuntungan Algoritma Sekuensial

1. **Kesederhanaan** – mudah dirancang, diterapkan, dan di-debug.
2. **Prediktabilitas** – hasil konsisten.
3. **Efisiensi (untuk tugas sederhana)** – bekerja baik untuk masalah kecil.

---

## Keterbatasan Algoritma Sekuensial

1. **Kurangnya Paralelisme** – tidak efisien untuk tugas bersamaan.
2. **Skalabilitas** – bisa lambat untuk masalah besar.
3. **Ketergantungan** – setiap langkah bergantung pada langkah sebelumnya.

---

## Perbandingan dengan Algoritma Paralel

| Aspek                | Algoritma Sekuensial                 | Algoritma Paralel                           |
| -------------------- | ------------------------------------ | ------------------------------------------- |
| **Eksekusi**         | Langkah dijalankan satu per satu     | Beberapa langkah berjalan bersamaan         |
| **Kecepatan**        | Lebih lambat untuk masalah besar     | Lebih cepat untuk tugas yang bisa paralel   |
| **Kompleksitas**     | Lebih mudah dirancang                | Lebih kompleks karena sinkronisasi          |
| **Kasus Penggunaan** | Cocok untuk masalah kecil dan linear | Cocok untuk tugas independen berskala besar |

---

## Kesimpulan

Algoritma sekuensial sangat penting dalam pemrograman dasar.
Mudah dan efektif untuk masalah kecil atau linear, namun memiliki keterbatasan pada kasus yang membutuhkan efisiensi tinggi atau pemrosesan paralel.

```

