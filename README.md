# GEOJSON0)

## Data GeoJSON Jaringan Jalan di Wilayah Sukaluyu, Bandung

Repositori ini berisi data geografis dalam format GeoJSON sebagai bagian dari pemenuhan tugas mata kuliah Sistem Informasi Geografis (SIG).

## Deskripsi Proyek

Tugas ini bertujuan untuk mengumpulkan data jaringan jalan (LineString) dari satu kelurahan/desa dan menyajikannya dalam format GeoJSON. Data ini kemudian divalidasi, disimpan di repositori GitHub, dan diimpor ke dalam database MongoDB.

## Detail File: `Daerah Rumah (rapet).geojson`

[cite_start]File `Daerah Rumah (rapet).geojson` [cite: 1] merupakan sebuah `FeatureCollection` yang berisi kumpulan data jalan di sekitar area Kelurahan Sukaluyu, Kota Bandung.

Setiap fitur dalam file ini merepresentasikan satu ruas jalan dan memiliki tipe geometri `LineString`.

### Struktur Data

Setiap jalan (fitur) memiliki data properti yang mendeskripsikan atribut jalan tersebut, antara lain:
-   [cite_start]`name`: Nama jalan (contoh: "Jalan Batik Tiga Negeri")[cite: 1].
-   [cite_start]`highway`: Tipe jalan (contoh: "residential", "living_street")[cite: 1].
-   [cite_start]`surface`: Jenis permukaan jalan (contoh: "asphalt", "concrete")[cite: 1].
-   [cite_start]`access`: Hak akses jalan (contoh: "private", "yes")[cite: 1].
-   [cite_start]`width`: Lebar jalan dalam meter[cite: 1].

Data ini dapat digunakan untuk keperluan visualisasi pada peta digital atau untuk analisis geografis lebih lanjut.


