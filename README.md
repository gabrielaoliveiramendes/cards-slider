# Cards Slider/Carrossel - Yu-Gi-Oh!

## Introdução
Este projeto web tem como objetivo criar um carrossel interativo de cartas de Yu-Gi-Oh!, permitindo ao usuário navegar por uma coleção de monstros icônicos do jogo.

## Funcionalidades
### Navegação Interativa:
  - Botões de Navegação: Os botões "Avançar" e "Voltar" permitem navegar entre as cartas de forma intuitiva. A funcionalidade é implementada utilizando addEventListener para escutar os eventos de clique nos botões e atualizar o índice da carta atual.
  - Atualização do Índice: A variável cartaoAtual é incrementada ou decrementada a cada clique nos botões, respectivamente, garantindo que a carta correta seja exibida.
### Gerenciamento de Estado:
  - Classe "selecionado": A classe "selecionado" é adicionada e removida dinamicamente das cartas para indicar a carta atualmente visível. Essa técnica permite controlar o estado visual das cartas e garantir que apenas uma carta seja exibida por vez.
### Refatoração de Código:
  - Funções: Para melhorar a organização e a reutilização do código, foram criadas funções específicas para mostrar e esconder as cartas. Essas funções recebem o índice da carta como parâmetro e aplicam as mudanças necessárias no DOM, como adicionar ou remover classes. Essa abordagem torna o código mais conciso e facilita a manutenção.
