<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/controller/reset.css">
    <link rel="stylesheet" href="/controller/style.css">
    <title>Combustível Ideal</title>
</head>

<body>
    <header class="cabecalho">
        <h1 class="cabecalho__titulo">COMBUSTÍVEL IDEAL</h1>
        <p class="cabecalho__paragrafo">Consulte qual o combustível ideal de acordo com os valores de sua região!</p>
    </header>
    <main>
        <form action="" class="formlario">
            <ul class="forulario__ord">
                <h3 class="titulo_lista">Gasolina</h3>
                <li class="formulario__lista">
                    <label for="" class="formulario__lista-label">Média km/L</label>
                    <input type="number" class="formulario__lista-input" id="media__gasolina" placeholder="Média">
                </li>
                <li class="formulario__lista">
                    <label for="" class="formulario__lista-label">Valor da Gasolina</label>
                    <input type="number" class="formulario__lista-input" id="valor__gasolina" placeholder="R$ 00.00">
                </li>

            </ul>
        </form>
        <form action="" class="formlario">
            <ul class="forulario__ord">
                <h3 class="titulo_lista">Álcool</h3>
                <li class="formulario__lista">
                    <label for="" class="formulario__lista-label">Média km/L</label>
                    <input type="number" class="formulario__lista-input" id="media__alcool" placeholder="Média">
                </li>
                <li class="formulario__lista">
                    <label for="" class="formulario__lista-label">Valor do Álcool</label>
                    <input type="number" class="formulario__lista-input" id="valor__alcool" placeholder="R$ 00.00">
                </li>

            </ul>

        </form>
    </main>

    <div id="distancia__estimada">
        <label for="" class="formulario__distancia-label"> Distância Estimanda</label>
        <input type="number" class="formulario__distancia-input" id="distancia__combustivel" placeholder="Distância em Km">
    </div>

    <div class="bot"><button id="botao">CALCULAR</button></div>

    <p id="resposta"></p>

    <footer>
        <p class="footer">&copy; TALLES C ARRIEL</p>
    </footer>
