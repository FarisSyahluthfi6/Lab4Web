# Lab4Web

| Nama= Faris Syahluthfi      | 
|-----------------------------|
| NIM= 312010034              |
|=============================| 
| Kelas= TI.20.A.1            |
|-----------------------------|
| Matkul= Pemrograman Web     |
|=============================|

## 1. Membuat Box Element
![Box_elemen](screenshot/Box_elemen.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag Membuat Box Element<p>
 Dan Ini Adalah program codingan dari tag Membuat Box Element:

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Box Element</title>
</head>
<body>
<header>
<h1>Box Element</h1>
</header>

<section>
    <div class="div1">Div 1</div>
    <div class="div2">Div 2</div>
    <div class="div3">Div 3</div>
    <div class="div4">Div 4</div>
    </section>

    </body>
</html>
 ```

 ## CSS Float Property
 Selanjutnya tambahkan deklarasi CSS pada head untuk membuat float element, seperti berikut:

 ```css
 <style>
        div {
        float:left;
        padding: 10px;
        }
        .div1 {
        background: rgb(129, 18, 18);
        }
        .div2 {
        background: rgb(139, 139, 35);
        }
        .div3 {
        background: rgb(39, 92, 39);
        }

        .div4 {
        background-color: rgb(47, 47, 117);
        clear: left;
        float: none;
        }
        
        </style>

 ```


## 2. Membuat Layout Sederhana
![Layout_Sederhana](screenshot/Layout_Sederhana.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag Membuat Layout Sederhana<p>
 Dan Ini Adalah program codingan dari tag Membuat Layout Sederhana:

## Contoh Kode
```Html
<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Layout Sederhana</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div id="container">
</div>

<header>
    <h1>WEBSITE FARIS SYAHLUTHFI</h1>
    </header>
    <nav>
    <a href="home.html" class="active">Home</a>
    <a href="artikel.html">Artikel</a>
    <a href="about.html">About</a>
    <a href="kontak.html">Kontak</a>
    </nav>
    <section id="hero"></section>
    <section id="wrapper">
    <section id="main"></section>
    <aside id="sidebar"></aside>
    </section>
    <footer>
    <p>&copy; 2022 - Faris Syahluthfi</p>
    </footer>


</body>
</html>
```

Kemudian tambahkan kode CSS untuk membuat layoutnya:
```css
/* import google font */
@import
url('https://fonts.googleapis.com/css2?family=Roboto&family=Rubik+Wet+Paint&display=swap');
@import
url('https://fonts.googleapis.com/css2?family=Roboto&family=Rubik+Wet+Paint&display=swap');
/* Reset CSS */
* {
margin: 0;
padding: 0;
}
body {
line-height:1;
font-size:100%;
font-family:'Open Sans', sans-serif;
color:#662424;
}
#container {
width: 980px;
margin: 0 auto;
box-shadow: 0 0 1em #cccccc;
}
/* header */
header {
padding: 20px;
}
header h1 {
margin: 20px 10px;
color: #b5b5b5;
}

```


## 4. Membuat Form
![Membuat_Form](screenshot/Membuat_Form.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag Membuat Form<p>
 Dan Ini Adalah program codingan dari tag Membuat Form:

 ```html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body bgcolor="brown">
    <style>
        form p > label {
        display: inline-block;
        width: 100px;
        }

        h1 {
	    color: #f0e9ee;
        font-size: 20px;
        text-align: center;
        }

        label {
	    color: #f0e9ee;
        font-size: 15px;
        text-align: center;
        }

        p1 {
	    color: #f0e9ee;
        font-size: 20px;
        text-align: center;
        }

        legend {
	    color: #f0e9ee;
        font-size: 20px;
        text-align: center;
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

        
<header>
<h1><center>PENDAFTARAN MAHASISWA BARU UNIVERSITAS PELITA BANGSA</center></h1>

<form action="proses.php" method="post">
    <fieldset>
    <legend><center><b>Registrasi Mahasiswa</b></center></legend>
    <p1><center><i>SILAHKAN ISI DATA DISINI...</i></center></p1>

    <p>
        <label for="nama">Nama:</label>
        <input type="text" id="nama" name="nama">
    </p>

    <p>
        <label for="Tempat_Lahir">Tempat Lahir:</label>
        <input type="text" id="tempat_lahir" name="tempat_lahir">
    </p>

    <p>
        <label for="tgl_lahir">Tanggal Lahir:</label>
        <input type="date" name="tgl_lahir" required><br>
    </p>

    <p>
        <label for="alamat">Alamat:</label>
        <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>

    <p>
        <label>Jenis Kelamin:</label>
        <input id="jk_l" type="radio" name="kelamin" value="L" /><label
        for="jk_l">Laki-laki</label>
        <input id="jk_p" type="radio" name="kelamin" value="P" /><label
        for="jk_p">Perempuan</label>
    </p>

    <p>
        
            <label>Agama:</label>
            <select name="agama">
                <option value="islam">Islam</option>
                <option value="kristen">Kristen</option>
                <option value="hindu">Hindu</option>
                <option value="budha">Budha</option>
            </select>
        
    </p>

<p><input type="submit" value="DAFTAR"></p>
</fieldset>
</form>

</header>
</body>
</html>

```

