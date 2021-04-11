# Praktikum 3 - Pemrograman Web
```
Veno Setyoaji Wiratama
311910363
TI.19.A.2
Universitas Pelita Bangsa
```

## LANGKAH 1
### Membuat dokumen HTML dengan nama file lab3_list.html. Setelah itu buat struktur dasar HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>HTML Lanjutan</title>
</head>
<body>
 <header>
 <h1>Membuat List</h1>
 </header>
</body>
</html>

```
![LANGKAH 1](https://user-images.githubusercontent.com/22215113/114301392-d1578580-9aee-11eb-9a93-8b78eb663538.png)

## LANGKAH 2
### Membuat Ordered List
```
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
    </ol>
</section>
```
![LANGKAH 2 membuat ordered list](https://user-images.githubusercontent.com/22215113/114301458-37dca380-9aef-11eb-9579-b0a9946965c8.png)

## LANGKAH 3
### Membuat Unordered List
```
<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma &amp; Pemrograman</li>
    </ul>
   </section>
```
![LANGKAH 3 membuat unordered list](https://user-images.githubusercontent.com/22215113/114301485-56db3580-9aef-11eb-8e04-011b03ef1ddc.png)

## LANGKAH 4
### Membuat Description List
```
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
![LANGKAH 4 membuat description list](https://user-images.githubusercontent.com/22215113/114301535-825e2000-9aef-11eb-8ba2-51fd8d24100f.png)

## LANGKAH 5
### Membuat dokumen HTML baru dengan nama file lab3_tabel.html. Setelah itu buat struktur dasar HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>HTML Lanjutan</title>
</head>
<body>
 <header>
 <h1>Membuat Table</h1>
 </header>
</body>
</html>
```
![LANGKAH 5 membuat table](https://user-images.githubusercontent.com/22215113/114301596-c05b4400-9aef-11eb-8d98-c9287172af4e.png)

## LANGKAH 6
### Membuat tabel dan mengatur margin tabel
```
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
```
![LANGKAH 6 membuat table dan mengatur margin](https://user-images.githubusercontent.com/22215113/114301697-2942bc00-9af0-11eb-91e2-526d72fb90ce.png)

## LANGKAH 7
### Menggabungkan Sel Data
```
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
```
![LANGKAH 7 menggabungkan sel data](https://user-images.githubusercontent.com/22215113/114301854-aec66c00-9af0-11eb-80a1-92eb76dee80f.png)

## LANGKAH 8
### Membuat dokumen HTML baru dengan nama file lab3_form.html dan Buat Tabel
```
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
```
![LANGKAH 8 membuat form](https://user-images.githubusercontent.com/22215113/114301931-07960480-9af1-11eb-8e62-aba524bca4d8.png)

## LANGKAH 8
### Menambahkan style pada form agar tampilan lebih menarik menggunakan CSS
```
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
![LANGKAH 9 menambahkan style pada form](https://user-images.githubusercontent.com/22215113/114301919-006ef680-9af1-11eb-9518-a23a5ec02ba2.png)

## TUGAS
### Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.

### Membuat Dropdown Menu
```
#CSS
	<style type="text/css">
	html,body{
		padding: 0;
		margin:0;
		font-family: sans-serif;
	}
 
	.menu{
		background-color: #ff7b00;
	}
 
	.menu ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		overflow: hidden;
	}
 
	.menu > ul > li {
		float: left;
	}
 
	
	.menu li a {
		display: inline-block;
		color: white;
		text-align: center;
		padding: 14px 16px;
		text-decoration: none;
	}
 
	.menu li a:hover{
		background-color: #ff7b00;
	}
 
	li.dropdown {
		display: inline-block;
	}
 
	.dropdown:hover .isi-dropdown {
		display: block;
	}
 
	.isi-dropdown a:hover {
		color: #fff !important;
	}
 
	.isi-dropdown {
		position: absolute;
		display: none;
		box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
		z-index: 1;
		background-color: #f9f9f9;
	}
 
	.isi-dropdown a {
		color: #3c3c3c !important;
	}
 
	.isi-dropdown a:hover {
		color: #232323 !important;
		background: #f3f3f3 !important;
	}
</style>
 
#Dropdown Menu 
<header class="header">
	<div class="menu">
 
		<ul>
			<li><a href="lab3_tugas.html">Home</a></li>
			<li class="dropdown"><a href="#">DROPDOWN MENU LAB 3 WEB</a>
				<ul class="isi-dropdown">
					<li><a href="lab3_list.html">LAB 3 LIST</a></li>
					<li><a href="lab3_tabel.html">LAB 3 TABEL</a></li>
					<li><a href="lab3_form.html">LAB 3 FORM</a></li>
				</ul>
			</li>
		</ul>
 
	</div>
</header>
```
![DROPDOWN](https://user-images.githubusercontent.com/22215113/114302050-88550080-9af1-11eb-8b56-079b5be08e7c.png)

### Membuat Listbox dengan multiple selection
```
<h4>CONTOH LISTBOX</h4>
<form action="proses.php" method="get">
    <p>Agama
    <select name='agama' multiple='multiple'>
      <option value='islam'>Islam</option>
      <option value='kristen' selected='selected'>Kristen</option>
      <option value='katholik'>Katholik</option>
      <option value='hindu'>Hindu</option>
      <option value='kristen'>Budha</option>
    </select>
    </p>
    <input type='submit' name='tombol' value='kirim' />
```
![LISTBOX](https://user-images.githubusercontent.com/22215113/114302083-a7539280-9af1-11eb-88a4-c5e94094b8b1.png)
