# Campo Minado em Java Swing

Este é um projeto simples do jogo Campo Minado desenvolvido em Java utilizando a biblioteca Swing para a interface gráfica.

## Funcionalidades

- **Interface Gráfica**: Utiliza `JFrame` para a janela principal, `JPanel` para organizar os componentes e `JButton` para representar cada célula do tabuleiro.
- **Tabuleiro**: Uma matriz bidimensional que representa o campo minado, onde cada célula pode conter uma mina ou um número indicando quantas minas estão ao redor.
- **Gerador de Minas**: Método para distribuir aleatoriamente as minas no tabuleiro.
- **Revelação de Células**: Ao clicar em um botão, revela se há uma mina ou um número. Se for um número zero, revela automaticamente as células adjacentes.
- **Marcação de Minas**: Possibilidade de marcar células suspeitas com bandeiras usando o botão direito do mouse.
- **Condições de Vitória e Derrota**: O jogador vence ao revelar todas as células que não contêm minas e perde ao clicar em uma célula com uma mina.
- **Atualização da Interface**: `JLabel` para mostrar informações como o número de minas restantes e o tempo decorrido, além de um botão para reiniciar o jogo.
