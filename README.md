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
    <div class="prawo">
        <fieldset>
<legend><h5>Przykładowe samochody u nas</h5></legend>
<img src="https://d-art.ppstatic.pl/kadry/k/r/1/d7/58/6256bdd039cc3_o_original.jpg" width="80%">
<img src="https://upload.wikimedia.org/wikipedia/commons/e/e4/BMW_i7_xDrive60_1X7A6424.jpg" width="80%">
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9d/Mercedes-AMG_G_63_Genf_2018.jpg" width="80%">
        </fieldset>
    </div>
    <div class="lewo">
        <fieldset>
            <legend><h4>Sponorzy</h4></legend>
    <img src="https://img.motozem.pl/files/photo_product/2/0/nalepka-red-bull.jpg" width="80%" >
    <img src="https://static.vecteezy.com/system/resources/previews/007/978/654/original/sprite-popular-drink-brand-logo-vinnytsia-ukraine-may-16-202-free-vector.jpg" width="80%">
        </fieldset>
    </div>  <main>
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
    <label for="dane pojazdu">
        <select name="marka" id="" value="Wybierz">
            <optgroup label="Wybierz markę pojazdu">
                <option value="1">Wybierz</option>
                <option value="2">Audi</option>
                <option value="3">BMW</option>
                <option value="4">Alfa Romeo</option>
                <option value="5">Volkswagen</option>
                <option value="6">Opel</option>
                <option value="7">Ford</option>
                <option value="8">Mercedes-Benz</option>
                <option value="9">Toytoa</option>
                <option value="10">Renault</option>
                <option value="11">Skoda</option>
                <option value="12">Peugeot</option>
                <option value="13">Ferrari</option>
                <option value="14">Bentley</option>
                <option value="15">Land Rover</option>
                <option value="16">Chevrolet</option>
                <option value="17">Lamborghini</option>
                <option value="18">Bugatti</option>
            </optgroup>
        </select>
    </label>
    <label for="dane pojazdu">
        <input type="text" name="model" placeholder="Wpisz model pojazdu"> 
    </label>
    <label for="dane pojazdu">
        <input type="color">Wybierz kolor pojazdu
    </label>
    <label for="dane pojazdu">
        <select name="paliwo" id="" value="Wybierz">
            <optgroup label="Wybierz rodzaj paliwa">
                <option value="1">Wybierz rodzaj paliwa</option>
                <option value="3">Benzyna</option>
                <option value="4">Benzyna+CNG</option>
                <option value="5">Benzyna+LPG</option>
                <option value="6">Diesel</option>
                <option value="7">Elektryczny</option>
                <option value="8">Etanol</option>
                <option value="9">Hybryda</option>
                <option value="10">Wodór</option>
          </optgroup>
        </select>
    </label>
    <label for="dane pojazdu">
        <select name="paliwo" id="" value="Wybierz">
            <optgroup label="Stan uszkodzeń">
                <option value="1">Wybierz stan uszkodzeń</option>
                <option value="2">Dowolnu</option>
                <option value="3">Nieuszkodzony</option>
                <option value="4">Uszkodzony</option>
          </optgroup>
        </select>
    </label>
    <form >
       Wybierz cenę pojazdu <input type="range" id="a" name="a" min="2000" max="400000" step=".5" oninput="result.value=a.value" />          
        <output name="result" for="a">0</output> PLN
    </form>
    <form >
        Rok produkcji <input type="range" id="a" name="a" min="1990" max="2023" step="" oninput="result.value=a.value" />          
         <output name="result" for="a">0</output>r.
     </form>
<label for="dane pojazdu">
    <form >
        Przebieg <input type="range" id="a" name="a" min="20000" max="250000" step="" oninput="result.value=a.value" />          
         <output name="result" for="a">20000</output> KM
     </form>
</label>
    </fieldset>
</main>
   


    




</div>
</body>
</html>
