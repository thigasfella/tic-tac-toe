# Tic Tac Toe
Bem-vindo ao repositório do Tic Tac Toe (Jogo da Velha)! Este projeto é uma implementação do clássico jogo da velha, onde dois jogadores se alternam para marcar os espaços em uma grade 3x3, com o objetivo de alinhar três de suas marcas em linha reta, coluna ou diagonal.

# Características
Modo de Dois Jogadores: Jogue contra um amigo no mesmo dispositivo.
Interface Responsiva: A interface se adapta a diferentes tamanhos de tela, incluindo dispositivos móveis.
Reinício de Jogo: Um botão de reiniciar está disponível para começar uma nova partida rapidamente.
Indicação de Turno: A interface mostra claramente de quem é a vez de jogar.

# Tecnologias Utilizadas

. HTML5: Estrutura do jogo.
. CSS3: Estilos e layout responsivo.
. JavaScript: Lógica do jogo e interação com o usuário.

# Como Jogar

Clonar o Repositório:
git clone https://github.com/seu-usuario/tic-tac-toe.git

Abrir o Arquivo HTML:
Navegue até o diretório do projeto e abra o arquivo index.html em seu navegador preferido.

Começar a Jogar:

Clique em uma das células da grade para fazer sua jogada.
Os jogadores se alternam entre "X" e "O".
O jogo anuncia o vencedor ou um empate quando todas as células estão preenchidas.
Use o botão "Reiniciar" para começar uma nova partida.

# Layout Responsivo
O layout foi projetado para ser responsivo e funcionar bem em várias resoluções de tela, garantindo uma boa experiência tanto em desktops quanto em dispositivos móveis.


@media (max-width: 600px) {
    body {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100vh;
        margin: 0;
        padding: 0;
        background-color: var(--bg-color);
    }

    #container {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
        flex-grow: 1;
        margin-top: 2px;
    }

    #jogo {
        width: 18rem;
        height: 18.3rem;
        border: 2px solid var(--tb-color);
        margin-bottom: 20px;
    }

    .linha {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .casa {
        width: 6rem;
        height: 6rem;
        border: 1px solid var(--tb-color);
    }

    #resetar {
        padding: 10px 20px;
        font-size: 0.8rem;
        cursor: pointer;
        border-radius: 5px;
        background-color: var(--btn-color);
        font-family: "Montserrat", sans-serif;
        font-weight: 700;
        margin-top: 10px;
        margin-bottom: 25px;
        color: var(--tb-color);
    }

    .nomesPlayers {
        margin: 0 auto;
    }

    .playerx,
    .playero {
        margin-bottom: 10px;
        border-bottom: 1px solid var(--tb-color);
    }

    .playerx input,
    .playero input {
        padding: 7px;
        font-family: "Montserrat", sans-serif;
        font-size: 14px;
        border-radius: 5px;
        width: 90%;
        max-width: 200px;
    }

    #name01,
    #name02 {
        width: 100%;
        height: auto;
        border: 1px solid var(--tb-color);
        border-radius: 5px;
        text-align: center;
        padding: 5px;
        box-sizing: border-box;
    }

    .jogadorX,
    .jogadorO,
    .nomeX,
    .nomeO,
    .vezJogador {
        display: flex;
        justify-content: center;
        margin-top: 5px;
        font-family: "Montserrat", sans-serif;
        font-weight: 200;
        font-size: 14px;
    }

    .container_vez {
        display: flex;
        align-items: center;
        margin: 0 auto;
    }

    .vez {
        font-family: "Montserrat", sans-serif;
        font-weight: 400;
        color: var(--tb-color);
        font-size: 14px;
    }

    .vez_name {
        font-family: "Montserrat", sans-serif;
        font-weight: 700;
        color: var(--vez-cor);
        font-size: 14px;
    }
}


Contribuição
Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades. Abra um pull request ou crie uma issue para discutir as mudanças que deseja fazer.


