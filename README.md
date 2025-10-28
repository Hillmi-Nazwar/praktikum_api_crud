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


## 1. Membuat Proyek Flutter baru.
<img width="1920" height="1080" alt="Screenshot (460)" src="https://github.com/user-attachments/assets/33883ed0-77d3-4870-a280-76cba04b111e" />


## 2. Menambahkan package http dibagian dependencies.
<img width="752" height="395" alt="Screenshot 2025-10-27 140011" src="https://github.com/user-attachments/assets/d1d21ea9-5137-4ca2-8a50-d468be56fa1c" />


## 3.  Simpan ke pubspec.yaml dengan perintah flutter pub get
<img width="910" height="488" alt="Screenshot 2025-10-27 135741" src="https://github.com/user-attachments/assets/3fe00df9-2b55-4a43-8773-89e85d7616a3" />


## 4. Code saat belum diperbaiki terjadi error

<img width="1920" height="1080" alt="Screenshot (459)" src="https://github.com/user-attachments/assets/b21e7cad-bd72-4d01-9f7e-1d4ab1d62500" />


Error ini terjadi karena pada beberapa syntak terlihat ada beberapa kesalahan penulisan seperti( Spasi berlebihan, tanda petik yang salah)
Dan setelah dilakukan perbaikan code bisa di run.

<img width="1920" height="1080" alt="Screenshot (461)" src="https://github.com/user-attachments/assets/d5c336bc-75e9-4cd2-af3f-13a8333fefc5" />



Tapi hasil ini masih belum sempurna karena masih ada perubahan data dan perubahan data.


## 5. Membuat Update dan Delete
 1.Implementasikan Update (PUT Request) UpdateUser di api_service.dart
 <img width="2020" height="5290" alt="carbon (1)" src="https://github.com/user-attachments/assets/78a7cb28-9d00-4f40-a982-21a6932f2016" />


 2. Buat halaman EditUserPage:
	Teks editing controller : 
<img width="1362" height="596" alt="carbon (2)" src="https://github.com/user-attachments/assets/9ac30c04-a1ca-46f3-8eee-9eb1122af3c0" />


  Update user : 

<img width="2020" height="856" alt="carbon (3)" src="https://github.com/user-attachments/assets/1d43d03c-765e-4ac4-aa41-49de0a6b8c90" />

  Api server :  
<img width="906" height="670" alt="carbon (4)" src="https://github.com/user-attachments/assets/2ca58a42-4115-4933-9e60-77d6d1d7b058" />


3. Integrasikan ke UserListPage
 Modifikasi onTap pada ListTile di buildUserListView untuk bernavigasi ke
 EditUserPage dan mengirim objek User.

<img width="1480" height="820" alt="carbon (5)" src="https://github.com/user-attachments/assets/f37b40f2-ce1a-47cf-9db8-654c9c050951" />


## 6. Implementasi DELETE (DELETE Request)

<img width="2002" height="894" alt="carbon (6)" src="https://github.com/user-attachments/assets/280bc74a-d088-41b7-8833-29b93450106a" />


# Hasil dan Kesimpulan 
## Hasil
  Saat menambahkan user
  
![Hasil](https://github.com/user-attachments/assets/5078ce18-bb82-4738-a5c9-afa1030fa8d4)

  User saat berhasil ditambahkan

![Hasil 2](https://github.com/user-attachments/assets/bf0862f2-fc4b-4de8-87c1-c020d3fdf822)

  Delete

![Delete](https://github.com/user-attachments/assets/e6a3616d-5a71-45b0-8e63-e13052051a88)


## Kesimpulan 
  Tugas Mobile Development ini berfokus pada Pengenalan Implementasi Dasar API Eksternal di mata kuliah Mobile Development. Inti dari tugas ini adalah berhasil menerapkan
seluruh operasi CRUD (Create, Read, Update, Delete) terhadap data pengguna melalui permintaan HTTP asinkron di Flutter , dengan menggunakan package http.
  Prosesnya melibatkan pengambilan data dari API (Read), mengurai data JSON(parsing) menjadi objek Dart (Model) , serta implementasi fungsi Create, Update, dan Delete
untuk mengelola data pengguna. Selain fungsionalitas, tugas ini juga mencakup penerapan styling dasar pada UI untuk menyajikan data dengan rapi.



