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
