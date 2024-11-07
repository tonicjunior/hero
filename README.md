# Jogo de Plataforma Dinâmica

## Visão Geral
Este jogo foi desenvolvido usando Phaser, um poderoso framework de jogos em HTML5. Ele apresenta uma experiência de plataforma dinâmica onde os jogadores devem navegar por vários desafios enquanto coletam moedas e evitam obstáculos.

## Recursos do Jogo
- **Plataformas Dinâmicas**: As plataformas aparecem e desaparecem, exigindo reflexos rápidos e bom tempo de reação.
- **Animação do Jogador**: Animações suaves para os movimentos do jogador, incluindo corrida e salto.
- **Efeitos Sonoros**: Música de fundo e efeitos sonoros que melhoram a experiência de jogo.
- **Design Responsivo**: O jogo se ajusta a diferentes tamanhos de tela.

## Instalação
Para executar o jogo localmente, siga estes passos:

1. Clone o repositório:
    ```bash
    git clone https://github.com/tonicjunior/hero.git
    cd hero
    ```

2. Instale as dependências (se aplicável):
    ```bash
    npm install
    ```

3. Abra o jogo:
    Abra `index.html` em seu navegador.

## Mecânicas do Jogo

### Controles
- **Interação com o Mouse**: Clique para crescer o mastro e navegar pelas plataformas.
- **Botões Responsivos**: Efeitos de hover nos botões para melhor interação do usuário.

### Opções do Jogo
O jogo inclui várias opções personalizáveis:
- **platformGapRange**: Define a distância entre as plataformas.
- **platformWidthRange**: Define a largura das plataformas.
- **playerWidth** e **playerHeight**: Dimensões do personagem jogador.

## Estados do Jogo
O jogo opera em vários estados:
- **IDLE**: O estado inicial quando nenhuma ação é tomada.
- **WAITING**: Quando está aguardando a entrada do jogador.
- **GROWING**: Quando o jogador está crescendo o mastro.
- **WALKING**: Quando o jogador está se movendo pelas plataformas.

## Recursos Utilizados
Os seguintes recursos são utilizados no jogo:
- Imagens para fundos, personagens e plataformas.
- Arquivos de áudio para música de fundo e efeitos sonoros.

## Notas de Desenvolvimento

### Funções Principais
- **sleep(miliseconds)**: Pausa a execução por uma duração especificada.
- **pause(miliseconds)**: Semelhante ao `sleep`, usada para temporização de eventos no jogo.

### Gerenciamento de Cenas
O jogo consiste em várias cenas:
- **preloadGame**: Lida com o carregamento de recursos antes do início do jogo.
- **playGame**: O loop principal de jogabilidade onde as interações ocorrem.
- **tutorial**: Um guia introdutório para novos jogadores.

## Diretrizes de Contribuição
Se você gostaria de contribuir para este projeto, por favor, faça um fork do repositório e envie um pull request com suas alterações.

## Licença
Este projeto é licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.
