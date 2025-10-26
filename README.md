# pratikum-tugas-pertemuan-6
#### Hasil program
![7](Gambar/Gambar05.png)

### Latihan 2
*Buat program sederhana dengan perulangan: program1.py
Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan
modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba. pada
bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5,
pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan
keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8
bulan berjalan usahanya.*

# Selesai :)
Python
modal = 1000000000
pendapatan = 0

for i in range(1,9,1):
    if i < 3: 
        laba = 0
        pendapatan = pendapatan + laba
    elif i < 5:
        laba = modal * 0.01
        pendapatan = pendapatan + laba
    elif i < 8:
        laba + modal * 0.05
        pendapatan + pendapatan + laba
    else:
        laba = modal * 0.02
        pendapatan = pendapatan + laba
    print("Laba bulan ke -", i, "sebesar: ", laba)
print("Total laba adalah: ", pendapatan)

penjelasan 
- if i in range(1,9,1) untuk mendeklarasikan perulangan 1-9
- if i < 3 jika i kurang dari bulan ke-3 maka laba/pendapatan = 0
- if i < 5 jika i kurang dari bulan ke-5 maka laba/pendapatan = 0.01
- if i < 8 jika i kurang dari bulan ke-8 maka laba/pendapatan = 0.05
- else: laba bulan terakhir = 0.02
- Menampilkan perulangan i pendapata/laba 
Python
    print("Laba bulan ke -", i, "sebesar: ", laba)
print("Total laba adalah: ", pendapatan)


#### Hasil program 
![8](Gambar/Gambar09.png)

# Selesai :)
