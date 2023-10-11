<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style2.css">
    <title>Document</title>
    <style>
        body {
            background-color: rgb(216, 106, 78);
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
<fieldset>
    <legend><h3>Dane pojazdu</h3></legend>
    <label for="dane pojazdu">
        <select name="podwozie" id="" value="Wybierz">
            <optgroup label="Wybierz typ podwozia">
                <option value="1">Wybierz</option>
                <option value="2">Auta małe</option>
                <option value="3">Auta miejskie</option>
                <option value="4">Coupe</option>
                <option value="5">Kabriolet</option>
                <option value="6">Kombi</option>
                <option value="7">Kompakt</option>
                <option value="8">Minivan</option>
                <option value="9">Sedan</option>
                <option value="10">SUV</option>
                <option value="11">Sportowe</option>
          </optgroup>
        </select>
    </label>
</fieldset>



    




</div>
</body>
</html>

