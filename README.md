# Movimentação de peças de xadrez

### Desafio Xadrez Programado: Dominando Estruturas de Repetição em C
Seja bem-vindo a uma jornada que transformará seus conhecimentos em habilidades práticas de programação! Imagine que você acabou de ser contratado pela MateCheck, uma empresa inovadora que desenvolve jogos para ensinar programação. Seu primeiro grande projeto?

### Um jogo de xadrez revolucionário!

Mas, calma, este não é um jogo comum. Aqui, as peças são controladas por linhas de código, exigindo que você domine a arte da programação para se tornar um verdadeiro mestre do xadrez virtual. Em vez de clicar e arrastar, você usará a lógica da programação em C para comandar cada peça, desafiando suas habilidades e aprendendo a fundo como estruturas de repetição funcionam na prática.

Dominar essas estruturas é essencial para se destacar no mercado de trabalho, permitindo criar sistemas complexos que exigem precisão e automação – habilidades cruciais na área de Tecnologia da Informação, para desenvolver jogos e muito mais.

Neste desafio, você vivenciará o dia a dia de um programador, construindo passo a passo a lógica por trás dos movimentos das peças. O projeto será dividido em três módulos com níveis de dificuldade crescente.


### 🎮 Módulo Novato: O Poder do Movimento Linear

No módulo novato, você dará os primeiros passos no tabuleiro, utilizando as estruturas de repetição básicas para controlar os movimentos lineares e contínuos das peças mais simples: a Torre, o Bispo e a Rainha.


### 🚩 Objetivo:

Implementar a lógica de cálculo de todas as casas válidas que a Torre, o Bispo e a Rainha podem alcançar a partir de uma posição inicial $(L, C)$, utilizando as estruturas de repetição: for, while e do-while.

### ⚙️ Funcionalidades do Sistema:

Entrada de Dados: O usuário informará as coordenadas de partida de uma peça (Linha e Coluna no tabuleiro $8\times 8$, por exemplo, de 1 a 8).

Movimento da Torre: O sistema usará um loop (ex: for ou while) para percorrer e exibir todas as casas válidas nas direções horizontal e vertical (linhas e colunas completas).

Movimento do Bispo: O sistema usará um loop (ex: while ou do-while) para percorrer e exibir todas as casas válidas nas quatro direções diagonais.

Movimento da Rainha: O sistema combinará a lógica da Torre e do Bispo, exibindo as casas válidas em todas as 8 direções.


## 🧩 Como compilar e executar

No terminal (CMD ou PowerShell), dentro da pasta do projeto:

```bash
gcc xadrez.c -o xadrez -Wall -Wextra -std=c11


```




### 🛡️ Módulo Aventureiro: A Complexidade do "L"

No módulo aventureiro, o desafio se intensifica: você implementará loops aninhados para orquestrar o intrigante e não linear movimento em "L" do Cavalo.

### 🆕 Diferença em relação ao Módulo Novato:

Loops Aninhados: Utilização de estruturas de repetição aninhadas para simplificar a identificação e o cálculo das 8 posições possíveis do Cavalo.

Restrição de Movimento: O sistema deve calcular apenas as 8 posições exatas que o Cavalo pode pular, diferentemente dos movimentos lineares e contínuos.

### ⚙️ Funcionalidades do Sistema:

Movimento do Cavalo: O sistema aceitará a posição inicial e usará loops (sugerido: aninhados com if ou arrays auxiliares) para calcular e exibir as coordenadas de todas as até 8 casas que o Cavalo pode atingir.

Validação de Limites: O sistema garantirá que apenas as casas dentro do tabuleiro $8\times 8$ (coordenadas de 1 a 8 ou 0 a 7, dependendo da sua implementação) sejam consideradas e exibidas.


## 🧩 Como compilar e executar

No terminal (CMD ou PowerShell), dentro da pasta do projeto:

```bash
gcc xadrez_AVENTUREIRO.c -o xadrez_AVENTUREIRO -Wall -Wextra -std=c11


```


### 🏆 Módulo Mestre: Otimização com Recursividade e Lógica Complexa

Por fim, no módulo mestre, você atingirá o auge da sua jornada, dominando a recursividade para otimizar os movimentos de longo alcance e utilizando loops complexos com múltiplas variáveis e condições para refinar seus códigos.


### 🆕 Diferença em relação ao Módulo Aventureiro:

Recursividade: Otimizar o cálculo dos movimentos da Torre e do Bispo (ou Rainha) implementando-o como uma função recursiva que calcula e exibe as casas em uma determinada direção até atingir a borda do tabuleiro.

Movimento do Peão: Implementação de loops com múltiplas condições e variáveis de controle para simular o movimento complexo do Peão:

Avanço de 1 casa.

Avanço opcional de 2 casas no primeiro movimento.

Ataque apenas na diagonal (e apenas 1 casa).


### ⚙️ Funcionalidades do Sistema:

Torre/Bispo Recursivo: Implementação de uma função recursiva para calcular e exibir os movimentos contínuos.

Movimento do Peão: O sistema calculará as casas válidas para o Peão, considerando:

A casa de partida.

O fato de ser ou não o primeiro movimento do Peão.

A distinção entre movimento de avanço e movimento de captura.

## 🧩 Como compilar e executar

No terminal (CMD ou PowerShell), dentro da pasta do projeto:

```bash
gcc xadrez_Mestre.c -o xadrez_Mestre -Wall -Wextra -std=c11


```







































































































































