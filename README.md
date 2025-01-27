# Jogo do Número Secreto

Este é um jogo simples desenvolvido com HTML, CSS e JavaScript, onde o jogador tenta adivinhar um número secreto gerado aleatoriamente pelo computador. O objetivo é descobrir o número com o menor número de tentativas possível.

---

## Funcionalidades

- O jogador pode chutar um número entre 1 e 10.
- O jogo informa se o chute está correto ou se o número secreto é maior ou menor.
- O jogo utiliza a biblioteca **ResponsiveVoice** para reproduzir áudio com mensagens em português.
- O botão "Novo Jogo" é habilitado apenas após o jogador acertar o número secreto.
- O jogo registra e exibe a quantidade de tentativas necessárias para acertar.
- Evita repetições no sorteio de números enquanto todos os números ainda não tiverem sido usados.

---

## Tecnologias Utilizadas

- **HTML5:** Estrutura do jogo.
- **CSS3:** Estilização responsiva e atraente.
- **JavaScript:** Lógica e interatividade do jogo.
- **ResponsiveVoice:** Biblioteca para síntese de voz.

---

## Estrutura do Projeto

- **index.html**: Contém a estrutura do jogo.
- **style.css**: Arquivo de estilização para o layout.
- **app.js**: Contém a lógica do jogo.
- **img/**: Pasta que armazena imagens utilizadas no jogo.

---

## Como Jogar

1. Abra o arquivo `index.html` em qualquer navegador.
2. Escolha um número entre 1 e 10 no campo de entrada.
3. Clique no botão **Aleatório** para verificar o chute.
4. Receba dicas se o número secreto é maior ou menor que o chute.
5. Quando acertar, o jogo informa o número de tentativas usadas.
6. Clique em **Novo Jogo** para jogar novamente.

---

## Funcionalidades do Código

### JavaScript

#### Geração de Número Aleatório
A função `gerarNumeroAleatorio()` gera um número entre 1 e 10 e garante que números repetidos só serão sorteados quando todos os números já tiverem sido utilizados.

#### Verificação do Chute
A função `verificarChute()` compara o chute do jogador com o número secreto e fornece feedback ao jogador através de texto e áudio.

#### Reinício do Jogo
A função `reiniciarJogo()` reinicia os parâmetros do jogo e desabilita o botão **Novo Jogo** até que o jogador acerte novamente.

#### Síntese de Voz
A biblioteca ResponsiveVoice é utilizada para converter mensagens de texto em áudio em português brasileiro.

---

## Requisitos

- Navegador moderno com suporte a JavaScript.
- Conexão com a internet para carregar a biblioteca ResponsiveVoice.

---

## Melhorias Futuras

- Adicionar um timer para medir o tempo gasto por rodada.
- Expandir o intervalo de números (ex.: 1 a 100) com opção de dificuldade.
- Implementar animações para melhorar a experiência do usuário.
- Criar versão mobile com otimizações adicionais para telas pequenas.

---

## Autor

Este projeto foi desenvolvido como um exemplo educativo para aprender interatividade com JavaScript e boas práticas de design e usabilidade.

---

## Licença

Este projeto está licenciado sob a Licença MIT. Sinta-se à vontade para usar, modificar e distribuir o código.

