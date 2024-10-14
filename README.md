# Lab3Web
Dita Tiara Putri (312310131)

# 1. Membuat Ordered List
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Html list</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
    </ol>
</section>
```
Penjelasan   
``<ol>``: Ordered list, digunakan untuk membuat daftar dengan urutan numerik (angka 1, 2, 3, dll.).   
``<li>``: List item, elemen untuk setiap item di dalam list. Pemrograman Web, Sistem Informasi, dan Basis Data 2.   
  
![Screenshot 2024-10-14 123508](https://github.com/user-attachments/assets/310dc6f5-8ecc-45f8-a5a1-d114e012331a)

# 2 Membuat Unordered List
```sh
<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
         <li>Jaringan Komputer</li>
         <li>Struktur Data</li>
         <li>Algoritma &amp; Pemrograman</li>
    </ul>
 </section>
```
Penjelasan   
``<ul>``: Unordered list, digunakan untuk membuat daftar tanpa urutan (biasanya menggunakan bullet points).  
type="square": Atribut untuk mengatur tipe bullet point, dalam hal ini berbentuk kotak (square).  
``<li>``: Sama seperti di ordered list, digunakan untuk setiap item dalam daftar.  

![Screenshot 2024-10-14 123917](https://github.com/user-attachments/assets/7694a1e9-cc48-49cd-b4ec-0f0b16172e86)

# 3. Membuat Description List
```sh
<section id="unorder-list">
    <h2>Description List</h2>
    <dl>
        <dt>Fakultas Teknik</dt>
        <dd>Teknik Industri</dd>
        <dd>Teknik Informatika</dd>
        <dd>Teknik Lingkungan</dd>
        <dt>Fakultas Ekonomi dan Bisnis</dt>
        <dd>Akuntansi</dd>
        <dd>Manajemen</dd>
         <dd>Bisnis Digital</dd>
    </dl>
</section>
```
Penjelasan   
``<dl>``: Description list, digunakan untuk membuat daftar definisi.   
``<dt>``: Definition term, digunakan untuk mendefinisikan istilah (dalam contoh ini nama fakultas).   
``<dd>``: Definition description, digunakan untuk menjelaskan atau mendeskripsikan istilah dari ``<dt>``. Setiap fakultas memiliki beberapa program studi yang dijelaskan dengan elemen ``<dd>``.   


![Screenshot 2024-10-14 124345](https://github.com/user-attachments/assets/f5f46b53-167f-4f5f-b6ab-336883ce568d)

# 4. Membuat tabel
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Html tabel</title>
</head>
<body>
    <header>
        <h1>Membuat tabel</h1>
    </header>
    
<table border="1" cellpadding="4" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td>Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik</td>
            <td>Teknik Lingkungan</td>
        </tr>
        </tbody>
        </table>
</body>
</html>
```
Penjelasan   
``<table>``: Elemen untuk membuat tabel.   
border="1": Atribut yang menambahkan garis batas pada tabel.   
``<thead>``: Bagian kepala tabel, digunakan untuk menampung judul kolom.   
``<tbody>``: Bagian isi tabel yang berisi data.   
``<tr>``: Table row, digunakan untuk membuat baris dalam tabel.   
``<th>``: Table header, digunakan untuk judul kolom.   
``<td>``: Table data, digunakan untuk menampilkan data dalam sel tabel.   

![Screenshot 2024-10-14 130254](https://github.com/user-attachments/assets/37e09f41-1dfe-4ffe-a0b9-c5f64b7e6752)

# Mengatur margin dan padding
```sh
<table border="1" cellpadding="6" cellspacing="0">
```
![Screenshot 2024-10-14 131517](https://github.com/user-attachments/assets/789c696d-e46c-45a0-b57f-d07b8fe2b565)

# 5. Menggabungkan Sel Data
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Html tabel</title>
</head>
<body>
    <header>
        <h1>Membuat tabel</h1>
    </header>
    
    <table border="1" cellpadding="6" cellspacing="0">
        <table border="1" cellpadding="6" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td rowspan="3">Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik Lingkungan</td>
            </tr>
            </tbody>
            </table>
</body>
</html>
```
Penjelasan   
rowspan="3": Atribut ini menggabungkan tiga baris pada kolom yang sama. Dalam contoh ini, kolom Fakultas (Teknik) digabung menjadi satu sel yang mencakup tiga baris.   

![Screenshot 2024-10-14 132743](https://github.com/user-attachments/assets/6ccbf763-c166-4b49-a9b7-44ce8e3693a7)

# 6. Membuat Form
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Html Form</title>
</head>
<body>
    <header>
        <h1>Membuat Form</h1>
    </header>
<form action="proses.php" method="post">
    <fieldset>
        <legend>Data Pelanggan</legend>
        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama">
        </p>
        <p>
            <label for="alamat">Alamat</label>
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
        </p>
        <p>
            <label>Jenis Kelamin</label>
            <input id="jk_l" type="radio" name="kelamin" value="L" /><label
        for="jk_l">Laki-laki</label>
        <input id="jk_p" type="radio" name="kelamin" value="P" /><label
        for="jk_p">Perempuan</label>
        </p>
        <p><input type="submit" value="Login"></p>
        </fieldset>
</form>
</body>
</html>
```
Penjelasan   
``<form>``: Elemen yang digunakan untuk membuat form.   
action="proses.php": Atribut yang menunjukkan bahwa data form akan dikirim ke file proses.php.   
method="post": Atribut untuk menentukan metode pengiriman data menggunakan HTTP POST.   
``<fieldset>``: Grup elemen form yang dikelilingi oleh kotak.   
``<legend>``: Judul untuk grup elemen di dalam ``<fieldset>``.   
``<input>``: Elemen untuk menerima input pengguna, misalnya teks atau tombol.   
``<textarea>``: Elemen untuk menerima input teks yang panjang (seperti alamat).   

![image](https://github.com/user-attachments/assets/ac65984f-2829-4132-99d7-f979b567b13d)

# Menambahkan Style pada Form
```sh
<style>
    form p > label {
        display: inline-block;
        width: 100px;
    }
    form input[type="text"], form textarea {
        border: 1px solid #197a43;
    }
    form input[type="submit"] {
        border: 1px solid #197a43;
        background-color: #197a43;
        color: #ffffff;
        font-weight: bold;
        padding: 5px 15px;
    }
</style>
```
Penjelasan   
display: inline-block;: Mengatur elemen label agar sejajar secara horizontal dengan input form.   
border: 1px solid #197a43;: Mengatur tampilan border (garis tepi) elemen input dan textarea dengan warna hijau gelap (#197a43).   
background-color: Mengatur warna latar belakang tombol submit menjadi hijau.   
padding: Mengatur ruang di dalam tombol submit.   

![image](https://github.com/user-attachments/assets/9ba7993f-f0b1-4cb6-a53f-804a93f63e9f)  

# TUGAS
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
```sh
   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form dengan Dropdown dan Listbox</title>
    <style>
        form p > label {
            display: inline-block;
            width: 120px;
        }
        form input[type="text"], form textarea, form select {
            border: 1px solid #197a43;
            width: 200px;
        }
        form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 5px 15px;
        }
        form select[multiple] {
            height: 100px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Form dengan Dropdown dan Listbox</h1>
    </header>

    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Pelanggan</legend>

            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama">
            </p>

            <p>
                <label for="alamat">Alamat</label>
                <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
            </p>

            <p>
                <label for="jk">Jenis Kelamin</label>
                <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="P" /><label for="jk_p">Perempuan</label>
            </p>

            <!-- Dropdown Menu -->
            <p>
                <label for="pekerjaan">Pekerjaan</label>
                <select id="pekerjaan" name="pekerjaan">
                    <option value="pelajar">Pelajar</option>
                    <option value="mahasiswa">Mahasiswa</option>
                    <option value="pegawai">Pegawai</option>
                    <option value="lainnya">Lainnya</option>
                </select>
            </p>

            <!-- Listbox with Multiple Selection -->
            <p>
                <label for="hobi">Hobi</label>
                <select id="hobi" name="hobi[]" multiple>
                    <option value="membaca">Membaca</option>
                    <option value="menulis">Menulis</option>
                    <option value="berolahraga">Berolahraga</option>
                    <option value="memasak">Memasak</option>
                    <option value="melukis">Melukis</option>
                </select>
            </p>

            <p>
                <input type="submit" value="Submit">
            </p>
        </fieldset>
    </form>
</body>
</html>
```   
Penjelasan   
Dropdown Menu (Select): Elemen select digunakan untuk membuat menu dropdown.   
``<option>``: Setiap opsi dalam dropdown memiliki nilai (value) yang akan dikirim ketika pengguna memilih opsi tersebut, dan teks yang ditampilkan kepada pengguna (misalnya, Pelajar, Mahasiswa). Pengguna hanya dapat memilih satu opsi dari daftar.   
Listbox: Menggunakan elemen select dengan atribut multiple, yang memungkinkan pengguna untuk memilih lebih dari satu opsi.   
name="hobi[]": Nama elemen ditulis dalam format array ([]) untuk menampung beberapa nilai yang dipilih pengguna.
Setiap opsi (misalnya, Membaca, Menulis, dll.) direpresentasikan oleh elemen ``<option>``.

   













