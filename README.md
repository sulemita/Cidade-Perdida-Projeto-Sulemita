# Cidade-Perdida
Projeto de aventura interativa desenvolvido com HTML, CSS e JavaScript, em que o jogador faz escolhas e percorre diferentes caminhos até encontrar a Cidade Perdida. O projeto inclui tela inicial personalizada, cenários ilustrados e múltiplos finais.
<!-- Tela inicial -->
<div class="passo ativo" id="capa">
    <img src="img/capa-aventura.png" alt="Capa da aventura">

    <h1>Em Busca da Cidade Perdida</h1>

    <p>
        Uma jornada misteriosa pela floresta amazônica em busca de segredos escondidos...
    </p>

    <button class="btn-proximo" data-proximo="0">
        Iniciar Aventura
    </button>
</div>


<!-- Primeiro passo da aventura -->
<div class="passo" id="passo-0">
    <img src="img/cenario-passo0.png" alt="Início da aventura">

    <p>
        Você começa sua jornada no Rio de Janeiro e encontra um mapa misterioso...
    </p>

    <button class="btn-proximo" data-proximo="1">
        Seguir para a montanha
    </button>

    <button class="btn-proximo" data-proximo="2">
        Explorar a floresta
    </button>
</div>
body{
    font-family: Arial, sans-serif;
    background: linear-gradient(#0d3b2a,#145a32);
    text-align:center;
    color:white;
}

.passo{
    display:none;
}

.passo.ativo{
    display:block;
}

#capa{
    margin-top:50px;
}

#capa img{
    width:300px;
    border-radius:20px;
}

h1{
    font-size:40px;
    margin-top:20px;
}

p{
    font-size:20px;
    max-width:600px;
    margin:auto;
}

button{
    background:#ffd700;
    color:black;
    border:none;
    padding:15px 30px;
    font-size:20px;
    border-radius:12px;
    margin-top:20px;
    cursor:pointer;
}

button:hover{
    transform:scale(1.05);
}
data-proximo="0"
