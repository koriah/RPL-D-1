<html>
<body>
<div align="center"><h1> DOKUMEN PENGUJIAN PERANGKAT LUNAK </h1></div>

<p align="center"><b>Version 1.0 </b><br>
<p align="center">9 Mei 2018</b>
<p align="center">
<img src="https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png" width="250" height="250"/ >
</p>

<p align="center"><b>Manajemen Administrasi Data Kependudukan Desa Lohbener <br>
</b>
<p align="center">Kelompok 1 <br>
 Hilmy Lazuardi            (1603099)<br>
 Ismatul Maula    (1603100)<br>
 jakaria       (1603101)<br><br><br>

<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b>
<p align="center"><b>2018</b>
</p>
</body>
</html>
 

**BAB I Pendahuluan**
----------
1.1 Tujuan Pembuatan Dokumen
----------

Dokumen ini digunakan sebagai panduan untuk melakukan pengujian terhadap perangkat lunak Manajemen Administrasi Data Kependudukan Desa Lohbener . Dokumen ini dipakai untuk melihat kemampuan dari program yang telah dirancang agar sesuai dengan keinginan dari pengguna. Pembuatan dokumen ini ditujukan untuk menguji perangkat lunak Manajemen Administrasi Data Kependudukan Desa Lohbener yang merupakan bagian dari tugas mata kuliah Rekayasa Perangkat Lunak.


1.2   Deskripsi Umum Sistem
----------

Perangkat lunak yang diuji adalah "Manajemen Administrasi Data Kependudukan Desa Lohbener " perangkat lunak ini adalah perangkat lunak yang digunakan untuk

1.3    Deskripsi Dokumen (Ikhtisar)
----------

Dalam dokumen ini berisi 3 bagian utama yaitu Pendahuluan, Identifikasi dan Rencana Pengujian, Deskripsi dan Uji Hasil.

1.4   Definisi dan Singkatan
----------

-  SKPL adalah Spesifikasi Kebutuhan Perangkat Lunak, atau dalam bahasa Inggris-nya sering juga disebut sebagai Software Requirements Spesification (SRS), dan merupakan spesifikasi dari perangkat lunak yang akan dikembangkan
- SKPL-SK.K-xxxx adalah kode yang digunakan untuk merepresentasikan kebutuhan (requirement) pada SK, dengan SK merupakan kode perangkat lunak, SK.K adalah kode fase, dan xxxx adalah digit/nomor kebutuhan (requirement)
- DFD adalah Data Flow Diagram, diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak.
- ERD adalah Entity Relationship Diagram, diagram dan notasi yang digunakan untuk merepresentasikan struktur data statis pada perangkat lunak.
- DPPL-Akkses.K-xxxx adalah kode yang digunakan untuk mengimplementasikan perancangan pada Akkses, dengan Akkses merupakan kode perangkat lunak, Akkses.Kadalah kode fase, dan xxxx adalahdigit/nomor perancangan.


1.5   Dokumen Referensi
----------

- Ernita H. GL03. Dokumen Uji Perangkat Lunak (DUPL) SDS. Bogor.
- Sistem Pentiketan Elektronik Konser.2013. Spesifikasi Kebutuhan Perangkat Lunak (SKPL)SPEK. Bogor
- Sistem Pentiketan Elektronik Konser.2013. Dokumen Perancangan Perangkat Lunak (DPPL)SPEK. Bogor.


**BAB II Lingkungan Pengujian Perangkat Lunak**
----------

2.1   Perangkat Lunak Pengujian
----------

Perangkat lunak ini Manajemen Administrasi Data Kependudukan Desa Lohbener diujikan dengan beberapa perangkat lunak lain, yaitu :

- Sistem operasi :Windows 10
- Bahasa pemograman : PHP
- Data base : XAMPP
- Framework : CodeIgniter

2.2  Perangkat Keras Pengujian
----------

Perangkat keras yang diperlukan untuk menguji aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener ini adalah satu set laptop dengan spesifikasi :

- Processor : Intel Core i5
- Memory : 4 GB DDR3
- Harddisk : 500 GB


2.3   Material Pengujian
----------

Pada program "Management Administrasi Data Kependudukan Desa Lohbener" ini diakses oleh sekdes. Sekdes sendiri dapat memanipulasi data kependudukan ,admin dapat mencetak laporan dengan memilih Id kategori laporan yang akan di filter berdasarkan kategori penduduk.setelah memilih id tersebut sekdes dapat memilih tanggal mulai data yang akan di ambil dan tanggal sampai data diambil





2.4   Sumber Daya Manusia
----------

Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujia perangkat lunak ini adalah :

- Memahami konsep pemograman berorientasi objek dalam bahasa PHP
- Memahami proses pengujian perangkat lunak berorientasi objek
- Memahami konsep pemrograman data base XAMPP


 
2.5   Prosedur Umum Pengujian
----------
**2.5.1 Pengenalan dan latihan**

Pengujian aplikasi ini diujikan oleh kita sebagai Developer. Pada dasar nya penguji memiliki kemampuan tentang pemograman PHP, Data base, dan Framework.

**2.5.2 Persiapan awal**

**2.5.2.1 Persiapan prosedural**

Pengujian ini dilakukan di area local (localhost) dimana pengujian ini dilakukan oleh kita sendiri sebagai Developer. alat yang digunakan 1 buah laptop dengan software yang telah diinstalasi.

**2.5.2.2  Persiapan Perangkat Keras**

Perangkat keras yang diperlukan adalah :
Sebuah perangkat komputer yang dilengkapi dengan :

- Processor : Intel Core i5
- Memory : 4 GB DDR3
- Harddisk : 500 GB

**2.5.2.3 Persiapan perangkat lunak**

Persiapan yang harus dilakukan untuk menyiapkan perangkat lunak untuk diuji di lingkungan sistem operasi Microsoft Windows 7 adalah sebagai berikut : 

-  Persiapkan sistem operasi Microsoft Windows. 
-  Perangkat lunak yang akan di uji di copy ke sebuah direktori, misalnya C:\XAMPP\htdocs. 
-  Browser Google Chrome. 
- Database di import ke phpMyAdmin di database db_konser. 
-  Adobe Dreamweaver atau notepad ++ untuk melihat source code

**2.3.5 Pelaksanaan**

Pelaksanaan pengujian dilakukan dengan mengeksekusi perangkat lunak Manajemen Administrasi Data Kependudukan Desa Lohbener dengan mengikuti skenario tertentu yang dibuat berdasarkan skenario yang terdapat pada dokumen SKPL-Manajemen Administrasi Data Kependudukan Desa Lohbener

**2.4.5 Pelaporan Hasil**

Dokumen hasil uji dari aplikasi ini akan diberikan kepada Pemerintahan Desa Lohbener sebagai mitra proyek kami . sehingga aplikasi mendapatkan umpan balik dalam pengembangan perangkat lunak ini selanjutnya.


BAB III Identifikasi dan Rencana Pengujian
----------
**Tabel 1 Identifikasi dan rencana Pengujian**

<table>  
	<thead>  
<tr>
	<td rowspan="2" align="center"><strong>Kelas Uji</td>
	<td rowspan="2" align="center"><strong>Butir Uji </td>
	<td colspan="2" align="center"><strong>Identifikasi</td>
	<td rowspan="2" align="center"><strong>Tingkat Pengujian</td>
	<td rowspan="2" align="center"><strong>Teknik Pengujian</td>
	<td rowspan="2" align="center"><strong>Penguji</td>
</tr>
		<tr>
			<td align="center"><strong>SRS/SDD</td>
			<td align="center"><strong>STD</td>
		</tr>
<tr>
	<td rowspan="3" align="center"><strong></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
<tr>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
	<td></td>
</tr>

</thead>  
</table>

BAB IV Deskripsi dan Hasil Uji
----------
**Tabel 2 Deskripsi dan Hasil Uji**

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3"></td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3"></td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3"></td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3"><br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3"></td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3"></td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li></li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li></li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

