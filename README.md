# GEOJSON

## Data GeoJSON: Di Area Sukaluyu
Repositori ini berisi file GeoJSON yang memetakan beberapa ruas jalan di area Sukaluyu, Bandung. Data ini dibuat sebagai bagian dari tugas mata kuliah Sistem Informasi Geografis.

## Deskripsi Data
File GeoJSON ini merupakan sebuah FeatureCollection yang berisi kumpulan fitur geografis. Setiap fitur merepresentasikan satu ruas jalan dalam bentuk LineString.

## Struktur Data
Struktur data untuk setiap jalan (fitur) dalam file ini cukup sederhana:

name: Properti utama yang berisi nama jalan (contoh: "Jalan Kawung Ece", "Jalan Batik Kumeli").
type: Menandakan bahwa objek ini adalah sebuah "Feature" GeoJSON.
properties: Objek ini saat ini kosong, karena informasi utama (nama jalan) ditempatkan di level atas.
geometry: Objek yang menyimpan data spasial:
type: Tipe geometri yang digunakan adalah LineString, cocok untuk merepresentasikan jalan atau garis.
coordinates: Sebuah array yang berisi dua atau lebih titik koordinat [longitude, latitude] yang membentuk garis jalan tersebut.

```
 {
      "name": "Jalan Kawung Picis",
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            107.63191570978813,
            -6.895971723601576
          ],
          [
            107.63247495748806,
            -6.897247505158731
          ]
        ],
        "type": "LineString"
      }
    }
```

Data ini siap digunakan!


