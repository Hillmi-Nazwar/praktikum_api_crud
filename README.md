# praktikum_api_crud

  TUGAS (CRUD & STYLING)
Pengenalan Implementasi Dasar API Eksternal

## Tujuan Praktikum
1. Memahami konsep dasar API (Application Programming Interface) dan REST API.
2. Menggunakan package http di Flutter untuk melakukan permintaan (request) ke
API eksternal.
3. Melakukan operasi CRUD (Create, Read, Update, Delete) terhadap data melalui
API.
4. Mengurai data JSON (parsing) dan mengubahnya menjadi objek Dart (Model).
5. Menampilkan data dari API ke dalam UI Flutter menggunakan widget seperti
ListView.
6. Mengimplementasikan styling dasar pada komponen UI untuk menyajikan data dengan rapi.
7. Mengelola state secara sederhana untuk menangani data yang bersifat asinkron
(asynchronous).


## Dasar Teori (penjelasan singkat tentang API, REST, JSON, http package).
API : Aplication Progamming Interface adalah sebuah aplikasi perangkat lunak berkomunikasi dan berinteraksi satu sama lain.

REST : Representational State Transfer, yaitu gaya arsitektur software untuk API yang berfokus pada komunikasi client-server melalui web

JSON : Java Script Object Notation, format pengukuran data berbasis tekas ringan dan mudah baik dibaca manuasi atau pun mesin.

http package : Adalah paket /pustaka dalam Bahasa pemograman seperti Dart,Python dll yang dirancang untuk memfasilitasi komunikasi menggunakan HyperText Tranfer Protocol (HTTP).


1. Membuat Proyek Flutter baru.


2. Menambahkan package http dibagian dependencies.


3.  Simpan ke pubspec.yaml dengan perintah flutter pub get


4. Code saat belum diperbaiki terjadi error



Error ini terjadi karena pada beberapa syntak terlihat ada beberapa kesalahan penulisan seperti( Spasi berlebihan, tanda petik yang salah)
Dan setelah dilakukan perbaikan code bisa di run.



Tapi hasil ini masih belum sempurna karena masih ada perubahan data dan perubahan data.

5. Membuat Update dan Delete
 1.Implementasikan Update (PUT Request) UpdateUser di api_service.dart
