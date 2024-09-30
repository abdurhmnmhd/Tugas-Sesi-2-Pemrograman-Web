Referensi WEB
https://www.nike.com/id/

1. DOCTYPE Declaration
<!DOCTYPE html>: Deklarasi jenis dokumen yang digunakan, yaitu HTML5.
2. HTML Document Root
<html lang="en">: Tag pembuka HTML, menandakan bahwa dokumen ini menggunakan bahasa Inggris.
3. Head Section
<head>: Bagian ini berisi informasi metadata dan sumber daya yang dibutuhkan halaman.
Title: <title>Nike. Just Do It. Nike ID</title>, judul halaman yang muncul di tab browser.
Script for Tailwind CSS: <script src="https://cdn.tailwindcss.com"></script>, digunakan untuk menghubungkan Tailwind CSS, sebuah framework CSS.
Font Awesome Stylesheet: <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>, digunakan untuk menambahkan ikon-ikon dari Font Awesome.
4. Body Section
<body class="bg-white">: Bagian utama dari dokumen yang memiliki kelas CSS untuk memberi latar belakang putih.
5. Header
<header class="flex justify-between items-center p-4 border-b">: Bagian header menggunakan Tailwind CSS untuk tata letak fleksibel (flexbox), dengan elemen-elemen diatur berjajar dan dibatasi dengan garis bawah.
Logo dan Icon Menu:
<i class="fas fa-bars text-xl"></i>: Ikon menu hamburger menggunakan Font Awesome.
<img src="./asset/Logo_Nike.png" alt="Nike logo" class="h-6" width="50" height="50"/>: Logo Nike dengan atribut lebar dan tinggi 50px.
Navigation Bar: <nav> berisi beberapa link (dalam bentuk <a>) seperti "New & Featured", "Men", "Women", "Kids", dll., masing-masing dengan efek hover.
Action Buttons:
<i class="fas fa-search text-xl"></i>: Ikon pencarian.
<i class="fas fa-heart text-xl"></i>: Ikon favorit.
<i class="fas fa-shopping-bag text-xl"></i>: Ikon keranjang belanja.
6. Main Content
Promotional Banner:
<div class="text-center py-4 bg-gray-100">: Div ini menampilkan pesan promosi dan link dengan kelas untuk menata teks dan latar belakang abu-abu.
<p class="text-sm">: Paragraf yang menampilkan teks kecil berisi informasi promosi.
<a href="#" class="text-sm text-blue-600 hover:underline">: Link untuk mengarahkan pengguna ke halaman markdown penjualan, dengan efek underline saat hover.
Hero Image:
<div class="w-full">: Div ini berisi gambar besar (hero image) yang memenuhi lebar layar.
<img src="https://cdn.runrepeat.com/storage/gallery/buying_guide_primary/1485/1485-best-nike-road-running-shoes-16425295-1440.jpg" alt="A person running on a road" class="w-full" width="1200" height="600"/>: Gambar dengan lebar penuh dan dimensi yang spesifik (1200px x 600px).
Komponen Utama:
Header: Berisi logo, ikon, navigasi, dan fitur pencarian, daftar keinginan, serta keranjang belanja.
Main Content: Berisi pesan promosi dan gambar besar yang mendominasi halaman.
Tata letak dan gaya halaman ini menggunakan Tailwind CSS dan ikon dari Font Awesome untuk membentuk desain antarmuka yang modern.