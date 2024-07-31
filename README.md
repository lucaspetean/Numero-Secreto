# Número Secreto

Este é um jogo simples de adivinhação de números, onde o objetivo é adivinhar o número secreto gerado aleatoriamente pelo computador.

## Funcionalidades

- O computador gera um número secreto aleatório.
- O jogador tenta adivinhar o número secreto.
- O jogo informa se a tentativa do jogador é maior ou menor que o número secreto.
- O jogo continua até que o jogador adivinhe o número secreto corretamente.

## Como Jogar

1. Clone este repositório:
    ```bash
    git clone https://github.com/lucaspetean/Numero-Secreto.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd Numero-Secreto
    ```

3. Abra o arquivo `index.html` em seu navegador.

4. Siga as instruções na tela para jogar o jogo.

## Estrutura do Projeto

- `index.html`: Contém a estrutura HTML do jogo.
- `styles.css`: Contém os estilos CSS para o jogo.
- `script.js`: Contém a lógica JavaScript para o jogo.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript

## O Que Eu Aprendi

Durante o desenvolvimento deste jogo, aprendi e apliquei os seguintes conceitos em JavaScript:

1. **Manipulação do DOM**: Utilizei métodos como `querySelector` e `innerHTML` para manipular elementos da página.
2. **Eventos**: Aprendi a capturar e responder a eventos do usuário, como cliques e entradas de texto.
3. **Funções**: Criei várias funções para modularizar e organizar o código, facilitando a manutenção e o entendimento.
    - `exibirTextoNaTela(tag, texto)`: Para exibir mensagens na tela e utilizar a biblioteca `responsiveVoice` para falar o texto.
    - `verificarChute()`: Para verificar se o chute do jogador está correto e fornecer feedback.
    - `gerarNumeroAleatorio()`: Para gerar um número aleatório e garantir que não se repita durante o jogo.
    - `limparCampo()`: Para limpar o campo de entrada após cada tentativa.
    - `reiniciarJogo()`: Para reiniciar o jogo, gerando um novo número secreto e resetando o contador de tentativas.
4. **Uso de Bibliotecas Externas**: Integrei a biblioteca `responsiveVoice` para adicionar feedback auditivo ao jogo.
5. **Controle de Fluxo**: Usei condicionais (`if`/`else`) para controlar a lógica do jogo e fornecer feedback ao jogador.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
