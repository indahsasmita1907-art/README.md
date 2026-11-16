# TUGAS 1 – AKUISISI DATA NYATA MELALUI API

## Akuisisi Data Tempat Wisata di Bali Menggunakan OpenStreetMap API

### 1. Identitas Mahasiswa
- Nama: Ni Putu Indahning Sasmita 
- NIM: 2501010104
- Program Studi: Informatika
- Mata Kuliah: Akuisisi dan Manajemen Data
- Institusi: INSTIKI

### 2. Deskripsi Proyek

Proyek ini merupakan tugas akuisisi data yang bertujuan untuk mengambil data nyata dari internet menggunakan Application Programming Interface (API).

Data yang diambil adalah informasi tempat wisata di wilayah Bali melalui OpenStreetMap. Data tersebut kemudian dikumpulkan, diolah, dibersihkan, dan disimpan menggunakan bahasa pemrograman Python melalui Google Colab.

### 3. Tujuan

1. Memahami proses pengambilan data menggunakan API.
2. Mengambil data nyata dari sumber terbuka.
3. Mengolah data menggunakan Python.
4. Menghasilkan dataset dalam format CSV dan JSON.
5. Memahami pentingnya sumber data, lisensi, dan etika pengambilan data.

### 4. Sumber Data

- Nama sumber: OpenStreetMap
- Website: https://www.openstreetmap.org/
- API: Overpass API
- Endpoint: https://overpass-api.de/api/interpreter
- Metode akuisisi: API
- Lisensi: Open Database License (ODbL)

### 5. Metode Pengambilan Data

Pengambilan data dilakukan menggunakan Overpass API dengan bahasa pemrograman Python.

Tahapan yang dilakukan:
1. Menghubungkan program dengan Overpass API.
2. Mengirim permintaan data tempat wisata di Bali.
3. Mengambil respons dalam format JSON.
4. Membersihkan dan mengolah data.
5. Menyimpan hasil pengolahan ke dalam CSV.
6. Menyimpan data mentah dalam format JSON.

### 6. Struktur Dataset

Dataset memiliki beberapa kolom sebagai berikut:

| No | Nama Kolom | Keterangan |
|---|---|---|
| 1 | nama | Nama tempat wisata |
| 2 | kategori | Jenis tempat wisata |
| 3 | latitude | Garis lintang |
| 4 | longitude | Garis bujur |
| 5 | website | Alamat website |
| 6 | alamat | Alamat tempat wisata |
| 7 | osm_type | Jenis objek OpenStreetMap |
| 8 | osm_id | ID objek OpenStreetMap |

### 7. Teknologi yang Digunakan

- Python
- Google Colab
- Pandas
- Requests
- JSON
- OpenStreetMap
- Overpass API
- GitHub

### 8. Hasil Akuisisi Data

Hasil pengambilan data disimpan dalam dua format, yaitu:

- CSV: tempat_wisata_bali.csv
- JSON: tempat_wisata_bali.json

Target dataset adalah minimal 100 record dengan minimal 5 kolom informasi.

Jumlah data akhir akan disesuaikan dengan hasil pengambilan data yang berhasil diperoleh dari API.

### 9. Data Provenance

Data provenance digunakan untuk mencatat asal-usul dataset, meliputi:
- Sumber data.
- Alamat API.
- Metode pengambilan data.
- Waktu akuisisi.
- Jumlah record.
- Jumlah kolom.
- Hash MD5 data mentah.

Dokumentasi provenance disimpan dalam file `docs/provenance.json`.

### 10. Etika Pengambilan Data

Pengambilan data dilakukan dengan memperhatikan beberapa ketentuan:
1. Menggunakan sumber data yang tersedia secara publik.
2. Mematuhi ketentuan penggunaan API.
3. Tidak melakukan permintaan berlebihan ke server.
4. Mencantumkan sumber data OpenStreetMap.
5. Memperhatikan lisensi Open Database License (ODbL).
6. Tidak mengubah data sehingga menyesatkan pengguna.

### 11. Struktur Repository

```text
Tugas1_AkuisisiData_NamaNIM/
│
├── notebooks/
│   └── akuisisi_tempat_wisata_bali.ipynb
│
├── data/
│   ├── raw/
│   │   └── tempat_wisata_bali.json
│   │
│   └── tempat_wisata_bali.csv
│
├── docs/
│   ├── provenance.json
│   └── data_ethics_checklist.csv
│
└── README.md
```

### 12. Kesimpulan

Melalui proyek ini, proses akuisisi data dapat dilakukan menggunakan API dari OpenStreetMap. Data yang diperoleh kemudian diolah menggunakan Python sehingga menghasilkan dataset yang dapat digunakan untuk analisis lebih lanjut. Proyek ini juga memberikan pemahaman mengenai pentingnya dokumentasi sumber data dan etika dalam pengambilan data.

---

**Sumber:** OpenStreetMap – https://www.openstreetmap.org/
