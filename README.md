# Jogo de Adivinhação 🎲

Bem-vindo ao **Jogo de Adivinhação**, um projeto simples e divertido desenvolvido em C! Teste suas habilidades de lógica e sorte enquanto tenta descobrir o número secreto gerado pelo programa.

## Descrição do Projeto
Este jogo desafia o jogador a adivinhar um número secreto entre 0 e 99. O jogador escolhe o nível de dificuldade, que determina a quantidade de tentativas disponíveis:

- **Fácil**: 20 tentativas
- **Médio**: 15 tentativas
- **Difícil**: 6 tentativas

A pontuação inicial é 1000 pontos e diminui a cada chute incorreto, dependendo da diferença entre o chute e o número secreto.

### Funcionalidades:
- Geração de número secreto aleatório.
- Três níveis de dificuldade para diferentes experiências de jogo.
- Mensagens visuais para vitória ou derrota.
- Controle de pontuação dinâmico.

## Como Jogar
1. Compile o programa com um compilador C, como `gcc`.
   ```bash
   gcc jogo_adivinhacao.c -o jogo_adivinhacao

2. Caso não tenha o compilador `gcc`, irei deixar o ".exe" do projeto.
