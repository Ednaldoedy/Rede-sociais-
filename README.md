<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Questionário sobre Redes Sociais</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
<h1>Questionário sobre Redes Sociais</h1>
<form id="questionario">
<label for="redeSocial">Qual rede social você mais usa?</label>
<select id="redeSocial">
<option value="facebook">Facebook</option>
<option value="instagram">Instagram</option>
<option value="whatsapp">WhatsApp</option>
<option value="x">X (antigo Twitter)</option>
<option value="linkedin">LinkedIn</option>
<option value="outros">Outros</option>
</select>

<label for="tempoConectado">Quanto tempo você fica conectado (em horas)?</label>
<input type="number" id="tempoConectado" min="0">

<label for="joga">Você joga?</label>
<select id="joga">
<option value="sim">Sim</option>
<option value="nao">Não</option>
</select>

<label for="tipoJogo">Qual tipo de jogo?</label>
<input type="text" id="tipoJogo">

<label for="tempoJogo">Quanto tempo você fica jogando (em horas)?</label>
<input type="number" id="tempoJogo" min="0">

<button type="submit">Enviar</button>
</form>

<div id="graficoContainer"></div>

<script src="script.js"></script>
</body>
</html>