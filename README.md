# Verificador-de-idade

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parte 3</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Verificador de idade</h1>
    </header>
    <section>
     <div>
        <p>Ano de Nascimento: 
            <input type="number" name="txtano" id="txtano" min="0">
        </p>
        <p>Sexo: 
            <input type="radio" name="radsex" id="masc" checked>
            <label for="masc">Masculino</label>
            <input type="radio" name="radsex" id="fem">
            <label for="fem">Feminino</label>
        </p>
        <p>
            <input type="button" value="verificar" onclick="verificar()">
        </p>
     </div> 
     <div id ="res">
        Preencha os dados acima para ver o resultado!
     </div>       
    </section>
    <footer>
        <p>&copy; CursoJavaScript</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
