# Geojson

<img width="1281" height="625" alt="image" src="https://github.com/user-attachments/assets/3ff78e72-4e60-4d9e-9241-5250608361e0" />

# Data GeoJSON: Jalan di Area Sukaluyu, Bandung
Repositori ini berisi file GeoJSON yang memetakan beberapa ruas jalan di area Sukaluyu, Bandung. Data ini dibuat untuk memenuhi tugas mata kuliah Sistem Informasi Geografis (SIG).

# Deskripsi Data
File GeoJSON ini merupakan sebuah FeatureCollection yang berisi kumpulan fitur geografis. Setiap fitur di dalamnya merepresentasikan satu ruas jalan dalam bentuk LineString. Data ini cocok digunakan untuk visualisasi pada platform pemetaan atau untuk analisis spasial lebih lanjut.

# Struktur Data
Setiap fitur jalan dalam koleksi ini mengikuti standar GeoJSON yang terdiri dari tiga bagian utama: type, properties, dan geometry.

type: Selalu bernilai "Feature" untuk menandakan bahwa objek ini adalah sebuah fitur geografis.
properties: Sebuah objek yang berisi atribut atau metadata deskriptif dari fitur tersebut.
name: Atribut utama yang menyimpan nama jalan, contohnya "Jalan Kawung Ece".
geometry: Sebuah objek yang menyimpan informasi spasial atau bentuk geografis dari fitur tersebut.
type: Tipe geometri yang digunakan adalah LineString, yang ideal untuk merepresentasikan jalan atau sungai.
coordinates: Sebuah array yang berisi dua atau lebih titik koordinat [longitude, latitude] yang membentuk garis jalan.

Contoh Data Satu Fitur Jalan
Berikut adalah contoh struktur untuk satu ruas jalan ("Jalan Kawung Ece") yang menunjukkan bagaimana data di atas diaplikasikan:
```
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "name": "Jalan Kawung Ece"
      },
      "geometry": {
        "coordinates": [
          [
            107.6312301076805,
            -6.89630217112277
          ],
          [
            107.63179767120198,
            -6.897594285992071
          ]
        ],
        "type": "LineString"
      }
    }
  ]
}
```
