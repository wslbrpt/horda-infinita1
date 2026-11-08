# Horda Infinita — Recomeço

Jogo de sobrevivência 2D em HTML5 Canvas, JavaScript puro e CSS. Sem bibliotecas externas, sem internet obrigatória e sem sistema de compilação.

## Executar no Android (Acode)
1. Extrai o ZIP preservando as pastas `css` e `js`.
2. Abre `index.html` no Acode.
3. Usa a opção de pré-visualização no navegador.

## Executar no computador
Abre `index.html` num navegador moderno. Usa WASD ou setas.

## Estrutura
- `index.html`: ecrã e interface
- `css/style.css`: layout responsivo e comandos táteis
- `js/game.js`: loop do jogo, hordas, combate, colisões e upgrades

## Recursos existentes
- Joystick tátil com Pointer Events; teclado WASD/setas
- Movimento independente da taxa de atualização
- Ataques automáticos, diferentes tipos de inimigos
- Cristais de XP, níveis e escolha de habilidades
- Pausa, reinício, interface adaptativa e limite de entidades
- Canvas com DPR limitado a 1.6 para reduzir custo de renderização

## Próximas fases
1. Substituir formas vetoriais por sprites/atlas otimizados.
2. Introduzir bosses, biomas, habilidades em área e efeitos.
3. Adicionar áudio opcional, menu de opções e progresso persistente.
4. Testar em dispositivos reais e perfilar desempenho.

## GitHub
Cria um repositório `horda-infinita` e envia estes ficheiros mantendo a estrutura. GitHub Pages pode servir este jogo como site estático.

## Licença
Código inicial criado para o projeto do utilizador; sem assets de terceiros.
