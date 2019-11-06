<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="style.css">
        <title>Taschenrechner</title>
    </head>
    <body>
        <h1>Dein Taschenrechner</h1>
        <br>
        
        <div id="div1">
        <p id="hello">Hallo, hier kannst du deine Berechnung starten:</p>
        <input type="value" name="Zahl eingeben" placeholder="Erste Zahl eingeben" id="eingabe1">
        <input type="value" name="Zahl eingeben" placeholder="Zweite Zahl eingeben" id="eingabe2">
        <br>
        <br>
        <button id="+" onclick="addieren()">+</button>
        <button id="-" onclick="subtrahieren()">-</button>
        <button id="*" onclick="multiplizieren()">x</button>
        <button id="/" onclick="dividieren()">/</button>
        <br>
        <br>
        <output id="ergebnis"></output>      
        <script src ="taschenrechner.js"></script>
        </div>

    </body>
</html>
