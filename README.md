<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <style>
        .navbar {
            background-color: #333;
            position: relative;
            z-index: 999;
        }

        .navbar ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        .navbar li {
            display: inline-block;
            position: relative; /* Untuk menempatkan submenu dengan benar */
        }

        .navbar li a {
            color: white;
            display: block;
            padding: 10px 20px;
            text-decoration: none;
        }

        .navbar ul ul {
            position: absolute;
            top: 100%;
            display: none;
            background-color: #333; /* Untuk mempertahankan gaya dropdown */
        }

        .navbar ul ul li {
            display: block;
        }

        .navbar li:hover > ul {
            display: block;
        }

        .navbar ul ul li a:hover {
            background-color: #555;
        }
    </style>
</head>

<body>

    <div id="halaman">
        <nav class="navbar"> <!-- Menambahkan kelas untuk styling -->
            <ul>
                <li><a href="#">Menu</a></li>
                <li>
                    <a href="#">dropdown</a>
                    <ul>
                        <li><a href="perpustakaan.html">Submenu-1</a></li>
                        <li><a href="buku.html">Submenu-2</a></li>
                        <li><a href="table pemesanan.html">Submenu-3</a></li>
                        <li><a href="Modul5 soal2.html">Modul 5-1</a></li>
                        <li><a href="Modul5 soal3.html">Modul 5-2</a></li>
                    </ul>
                </li>
            </ul>
        </nav>
    </div>

</body>
</html>

<h1>PERPUSTAKAAN UNIVERSITAS NEGERI MEDAN</h1>

<h2>Perkenalkan saya Metharia Jessica, ini adalah pengalaman pertama saya dalam membuat Website untuk memenuhi tugas matakuliah Pemograman Web. Perpustakaan yang saya ambil adalah Perpustakaan Unimed selengkapnya mengenai perpustakaan unimed dapat dilihat melalui link yang disertakan https://perpustakaan.unimed.ac.id/</h2>

![WhatsApp Image 2024-09-22 at 19 57 41](https://github.com/user-attachments/assets/39e963ec-fc2f-4451-8cb7-2aa81ee63a35)

<div class="dropdown">
        <button class="mainmenubtn">Main Menu</button>
        <div class="dropdown-child">
            <a href="http://www.yourdomain.com/page1.html">Sub Menu 1</a>
            <a href="http://www.yourdomain.com/page2.html">Sub Menu 2</a>
            <a href="http://www.yourdomain.com/page3.html">Sub Menu 3</a>
            <a href="http://www.yourdomain.com/page4.html">Sub Menu 4</a>
            <a href="http://www.yourdomain.com/page5.html">Sub Menu 5</a>
        </div>
Berikut video profile Perpustakaan Universitas Negeri Medan
https://youtu.be/e8DYUPu3PuM?feature=shared

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>AUDIO/AUTOPLAY</title>
</head>
<body>
  <h1>AUDIO/AUTOPLAY</h1>
  <audio controls>
    <source src="start.mp3"type=audio/mpeg>
  </audio>
</body>
</html>
<html>
<body>
<h2>Formulir Perpustakaan Universitas Negeri Medan</h2>
    <form action="#" method="post">
        <table>
            <tr>
                <th>Nama</th>
                <td><input type="text" name="nama" required></td>
            </tr>
            <tr>
                <th>NIM</th>
                <td><input type="text" name="nim" required></td>
            </tr>
            <tr>
                <th>Alamat</th>
                <td><textarea name="alamat" rows="3" required></textarea></td>
            </tr>
            <tr>
                <th>Jenis Kelamin</th>
                <td>
                    <input type="radio" name="jenis_kelamin" value="Laki-laki" required> Laki-laki
                    <input type="radio" name="jenis_kelamin" value="Perempuan" required> Perempuan
                </td>
            </tr>
            <tr>
                <th>Email</th>
                <td><input type="email" name="email" required></td>
            </tr>
            <tr>
                <th>No HP</th>
                <td><input type="text" name="no_hp" required></td>
            </tr>
            <tr>
                <th>Tempat Lahir</th>
                <td><input type="text" name="tempat_lahir" required></td>
            </tr>
            <tr>
                <th>Tanggal Lahir</th>
                <td><input type="date" name="tanggal_lahir" required></td>
            </tr>
        </table>
        <br>
        <input type="submit" value="Submit">
    </form>
</body>      
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabel Bahan Buku</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Daftar Bahan Buku</h1>
    <table>
        <thead>
            <tr>
                <th>No</th>
                <th>Judul Buku</th>
                <th>Pengarang</th>
                <th>Penerbit</th>
                <th>Tahun Terbit</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>The Joy Of Missing Out</td>
                <td>Tanya Dalton</td>
                <td>PT Bentang Pustaka</td>
                <td>2021</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Her Name Is</td>
                <td>Karya Cho Nam Joo</td>
                <td>Bhuana Ilmu Populer</td>
                <td>2021</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Le Petit Princea</td>
                <td>Antoine de Saint-Exupéry</td>
                <td>Gramedia Pustaka Utama</td>
                <td>2022</td>
            </tr>
            <tr>
                <td>4</td>
                <td>Filosofi Teras</td>
                <td>Henry Manampiring</td>
                <td>Penerbit Buku Kompas</td>
                <td>2019</td>
            </tr>
        </tbody>
    </table>
</body>
<body>
<h2>Formulir Pemesanan Buku</h2>
    <form action="#" method="post">
        <table>
            <tr>
                <th>Nama</th>
                <td><input type="text" name="nama" required></td>
            </tr>
            <tr>
                <th>Nomor Anggota Perpustakaan</th>
                <td><input type="text" name="nomor anggota perpustakaan" required></td>
            </tr>
            <tr>
                <th>Tanggal Pemesanan</th>
                <td><textarea name="Tanggal Pemesanan" rows="3" required></textarea></td>
            </tr>
            <tr>
                <th>Jenis Kelamin</th>
                <td>
                    <input type="radio" name="jenis_kelamin" value="Laki-laki" required> Laki-laki
                    <input type="radio" name="jenis_kelamin" value="Perempuan" required> Perempuan
                </td>
            </tr>
            <tr>
                <th>Email</th>
                <td><input type="email" name="email" required></td>
            </tr>
            <tr>
                <th>No HP</th>
                <td><input type="text" name="no_hp" required></td>
            </tr>
            <tr>
                <th>Penulis Buku</th>
                <td><input type="text" name="Penulis Buku" required></td>
            </tr>
            <tr>
                <th>No ISBN</th>
               <td><input type="text" name="no isbn" required></td>
            </tr>
             <tr>
                <th>Judul Buku Yang Dipesan</th>
                <td><input type="text" name="judul buku yang dipesan" required></td>
            </tr>
        </table>
        <br>
        <input type="submit" value="Submit">
</body>
      <body>
<h2>Formulir Perpanjangan peminjaman buku </h2>
    <form action="#" method="post">
        <table>
            <tr>
                <th>Nama</th>
                <td><input type="text" name="nama" required></td>
            </tr>
            <tr>
                <th>Nomor Anggota Perpustakaan</th>
                <td><input type="text" name="nomor anggota perpustakaan" required></td>
            </tr>
            <tr>
                <th>Tanggal Pemesanan</th>
                <td><textarea name="Tanggal Peminjamanan" rows="3" required></textarea></td>
            </tr>
            <tr>
                <th>Email</th>
                <td><input type="email" name="email" required></td>
            </tr>
            <tr>
                <th>No Telepon</th>
                <td><input type="text" name="no telepon" required></td>
            </tr>
            <tr>
                <th>No ISBN</th>
                <td><input type="text" name="no isbn" required></td>
            </tr>
             <tr>
                <th>Tanggal Perpanjangan Buku</th>
                <td><input type="date" name="Tanggal perpanjangan buku" required></td>
            </tr>
        </table>
        <br>
        <input type="submit" value="Submit">
    </form>
    
        <h1> Pengertian HTML dan CSS </h1>
        <p>HTML adalah bahasa markup standar yang digunakan untuk membuat struktur dan konten halaman web. Dalam HTML, pengembang web mendefinisikan elemen-elemen seperti teks, gambar, tautan, formulir, dan elemen lainnya yang membentuk tampilan halaman web. HTML menggunakan tag-tag untuk menandai elemen-elemen ini sehingga peramban web tahu cara menampilkan mereka.</p>
    
        <p>CSS adalah bahasa stylesheet yang digunakan untuk mengontrol tata letak dan tampilan halaman web. Dengan CSS, Anda dapat mengatur warna, ukuran, spasi, jenis font, dan banyak properti tata letak lainnya untuk elemen-elemen HTML. Penggunaan CSS memungkinkan pemisahan antara struktur dan tata letak, sehingga HTML dapat fokus pada struktur konten, sementara CSS mengontrol cara konten tersebut ditampilkan.</p>
    
</html>
