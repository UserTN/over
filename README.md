# over<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>meu mundo</title>
    <style>
        /* Para evitar que o botão 'Não' seja clicado */
        button.no-button {
            pointer-events: none;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #cd60db;
            text-align: center;
            margin: 0;
            padding: 20px;
        }

        h1 {
            color: #4407eb;
            font-size: 32px;
            margin-bottom: 20px;
        }

        h5 {
            color: #810877;
            font-size: 20px;
            margin-top: 10px;
            margin-bottom: 30px;
        }

        button {
            background-color: #0ae93a;
            color: #fff;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
            margin-right: 10px;
        }

        button:hover {
            background-color: #08a8f3;
        }

        p {
            color: #750a06;
            font-size: 14px;
            margin-top: 50px;
        }
    </style>
</head>
<body>
    <h1>BEM VINDA! ESTAVA EM SUA ESPERA...</h1>
    <p><strong>COLOQUE SEU FOME E RELEXE!</strong></p>
    <h5>está pronto(a)?</h5>
    <button id="sim-button" onclick="abrirLink()"><h4>Sim</h4></button>
    <button class="no-button"><h4>Não</h4></button>

    <p>ass:ânonimoUserTN</p>

    <script>
        function abrirLink() {
            // Altere o URL abaixo para o link desejado
            window.location.href = 'https://www.youtube.com/watch?v=NMagMBZs73c&t=44s';
        }
    </script>
</body>
</html>
