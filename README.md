# Atividade 2 — Fluxogramas

**Curso:** Web Academy UFAC  
**Disciplina:** Algoritmos e Lógica de Programação  
**Aluno:** Vinicius Miranda de Farias

## Questão 1 — Conceitual (2,5 pontos)

### 1. O que é um fluxograma e sua finalidade prática

Fluxograma é uma representação gráfica de um procedimento, problema ou sistema, cujos passos são ilustrados de forma encadeada por meio de símbolos geométricos interconectados — ou seja, um diagrama de fluxo. Na prática, ele serve como documentação visual dos passos necessários para executar um algoritmo, mostrando a sequência de ações e as decisões tomadas ao longo do processo.

### 2. Principal vantagem e limitação

A principal vantagem é permitir uma **visualização global do processo** de resolução do problema: quem lê o fluxograma entende rapidamente o caminho percorrido pelo algoritmo. A limitação é que, em problemas de maior complexidade, o fluxograma pode se tornar muito grande e extenso, dificultando a leitura, a manutenção e a compreensão do diagrama.

## Questão 2 — Mapeamento de Simbologia (2,5 pontos)

| Forma geométrica | Significado | Pseudocódigo correspondente |
| --- | --- | --- |
| **a) Elipse** | **Terminal**: demarca os pontos de início e fim do algoritmo. | `INÍCIO` e `FIM` |
| **b) Paralelogramo** | **Entrada ou saída de dados**: mostra dados recebidos do ambiente externo ou fornecidos a ele. | `LEIA()` e `ESCREVA()` |
| **c) Retângulo** | **Processo**: representa um passo (operação) do algoritmo, como cálculos e atribuições. | Comandos de processamento, ex.: `R <- X + Y` |
| **d) Losango** | **Condição**: indica uma situação em que o algoritmo segue uma ou outra direção conforme o resultado da condição. | `SE ... ENTÃO ... SENÃO` |

## Questão 3 — Teoria de Linguagem (2,5 pontos)

### Diferença entre sintaxe e semântica no pseudocódigo

- **Sintaxe** está relacionada aos aspectos de **estrutura e forma**. É o conjunto de regras que determina como escrever e combinar palavras, frases e sentenças válidas na linguagem. No pseudocódigo, significa seguir a forma correta dos comandos, por exemplo: `INÍCIO`, `LEIA(X)`, `SE (X > Y) ENTÃO ... SENÃO ... FIMSE`, `FIM`.
- **Semântica** está relacionada ao **significado**, ao entendimento dessas construções. Define o que cada comando realmente faz: `LEIA()` obtém um dado do usuário, `ESCREVA()` apresenta um resultado, `SE...ENTÃO...SENÃO` desvia o fluxo conforme uma condição.

Em resumo: a sintaxe cuida de **como escrever** o algoritmo; a semântica cuida de **o que cada parte significa e executa**. Conhecendo as duas, é possível “comunicar-se” com o computador, como destaca o material da Aula 2. O pseudocódigo (também chamado de portuguol, nome derivado de Algol) aproxima essa comunicação da linguagem natural e facilita a tradução para linguagens de alto nível.
