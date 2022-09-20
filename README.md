<!DOCTYPE html>
<html lang="cz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styly.css">
    <title>Projekt ke zkoušce</title>
</head>
<body>
  <header>
          
            <h3>POJIŠTĚNÍ</h3> 
            <div>
            <a href=" Pojistenci.html "> Pojištěnci </a>
            <a href=" O aplikaci.html "> O aplikaci</a> 
            </div>
    </header>
    
        <div>
            <div class="main-flex">
            <h3> Pojištěnci </h3>  
        
        <table border="1" class="tabulka-pojistenych">
            <thead>
                <th>Jméno a přijmení</th>
                <th> Telefon</th></br>
                <th> Věk</th>
            </thead>
        </table>
        </div>

            <h3>Nový pojištěnec</h3>
        <form>
            Jméno <input class="jmeno" type="text">
            Příjmení <input class="prijmeni" type="text">
            Telefonní číslo <input class="telefon" type="number">
            Věk <input class="vek" type="number">           
            <a href="#" class="button">Uložit pojištěnce</a>
            
        </form>
    </div>

    <script src="index.js"></script>
    <script src="Pojistenec.js"></script>

</body>

</html>


