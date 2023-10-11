<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style2.css">
    <title>Document</title>
    <style>
        body {
            background-color: rgb(67, 120, 236);
            display: flex;
            justify-content: center;
        }
    </style>
</head>
<body>
    <div class="container">
    <header>
    <div class="gora"><h1>Formularz o kupno auta</h1></div>
    </header>
<fieldset>
    <legend><h2>Dane</h2></legend>
    <label for="dane">
        <input type="text" name="imie" required placeholder="Wpisz swoje imie">
    </label>
    <label for="dane">
        <input type="text" name="nazwisko" required placeholder="Wpisz swoje nazwisko">
    </label>
    <label for="dane">
        <input type="text" name="wiek"  required placeholder="(dd.mm.rrrr)">
    </label>
    <label for="dane">
        <input type="text" name="miasto" required placeholder="Podaj miasto">
    </label>
    <label for="dane">
        <input type="radio" name="mężczyzna"> Mężczyzna
    </label>
    <label for="dane">
        <input type="radio" name="kobieta"> Kobieta
    </label>
</fieldset>



    




</div>
</body>
</html>
