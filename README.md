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


## 4. Membuat Navigasi
![Membuat_Navigasi](screenshot/Membuat_Navigasi.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag Membuat Navigasi<p>
 Dan Ini Adalah program codingan dari tag Membuat Navigasi:

 ```css

/* navigasi */
nav {
    display: block;
    background-color: #df1e28;
    }
    nav a {
    padding: 15px 30px;
    display: inline-block;
    color: #ffffff;
    font-size: 14px;
    text-decoration: none;
    font-weight: bold;
    }
    nav a.active,
    nav a:hover {
    background-color: #111010;
    }

```

## 5. Membuat Hero Panel.
Selanjutnya membuat hero panel. Tambahkan kode HTML dan CSS seperti berikut:

```html
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

    <section id="hero">
        <h1>Selamat datang...</h1>
        <p>Halo semuanya selamat datang di website saya. website ini adalah tempat belajar membuat website</p>
        <a href="home.html" class="btn btn-large">Learn more &raquo;</a>
        </section>
        <footer>
    <p>&copy; 2022 - Faris Syahluthfi</p>
    </footer>


</body>
</html>

```

```css
 /* Hero Panel */
#hero {
    background-color: #e4e4e5;
    padding: 25px 25px;
    margin-bottom: 25px;
    }
    #hero h1 {
    margin-bottom: 50px;
    font-size: 35px;
    }
    #hero p {
    margin-bottom: 50px;
    font-size: 18px;
    line-height: 50px;
    }

```

## Hasil dari kodingan diatas:
![Hero_panel](screenshot/Hero_panel.PNG)

