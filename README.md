<h1 align="center">Jogo do número secreto</h1>
<p align="center">
  <img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=red&style=for-the-badge"/>
</p>

## 📎 Objetivo
Este projeto tem como objetivo principal reforçar a lógica de programação utilizando JavaScript.  
Além de praticar estruturas condicionais, funções e eventos, o projeto permite:

- Desenvolver habilidades de manipulação do DOM para exibir informações dinâmicas.
- Trabalhar com arrays para controlar números já sorteados, evitando repetição.
- Aplicar validações de entrada e controle de fluxo do jogo.
- Criar uma experiência interativa, com mensagens de feedback por texto e voz.
- Compreender a importância de organizar o código em funções claras e reutilizáveis.

## 📝 Desenvolvimento
O projeto foi desenvolvido utilizando JavaScript, HTML e CSS, aplicando conceitos essenciais de lógica de programação:

- **Estruturas condicionais** (`if` / `else`) para comparar o palpite do usuário com o número secreto.
- **Funções** para organizar o código em tarefas específicas: gerar número aleatório, exibir mensagens, limpar campos e reiniciar o jogo.
- **Manipulação do DOM** para atualizar textos, habilitar/desabilitar botões e capturar valores do input.
- **Array para controle de números sorteados**: Evita repetição de números até que todos sejam utilizados.
- **Interação por voz**: Uso do `responsiveVoice` para tornar o jogo mais interativo, lendo instruções e feedbacks para o jogador.
- **Controle de fluxo**: A lógica garante que o jogador só possa prosseguir se as condições forem atendidas (palpite válido, reinício do jogo, etc.).

## :hammer: Funcionalidades
- **Geração de número secreto aleatório**: O computador escolhe um número entre 1 e 100 que o jogador deve adivinhar.
- **Evita repetição de números**: Cada número gerado é único até que todos os números do intervalo sejam sorteados.
- **Comparação de palpites**: Informa se o número digitado é maior ou menor que o número secreto.
- **Contagem de tentativas**: Mostra quantas tentativas o jogador precisou para acertar.
- **Feedback instantâneo por voz e texto**: As mensagens na tela são lidas em voz alta usando a biblioteca `responsiveVoice`.
- **Reinício do jogo**: Permite reiniciar o jogo com um novo número secreto sem recarregar a página.
- **Validação e limpeza do campo de input**: Evita entradas inválidas e limpa o campo automaticamente após cada tentativa.


Durante o desenvolvimento, o foco foi criar uma experiência interativa e funcional, reforçando os conceitos de lógica, manipulação de arrays, funções e eventos em JavaScript.
## ✔ Técnicas e tecnologias utilizadas
- **HTML, CSS e JavaScript**
- **IDE VS Code**

## 🎮 Você pode testar o jogo
- https://jogo-do-numero-secreto-gold-ten.vercel.app/
