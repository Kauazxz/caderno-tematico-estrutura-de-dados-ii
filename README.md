# Caderno Temático com NotebookLM: Estrutura de Dados em C

## Sobre o projeto

Este repositório foi desenvolvido como parte de um desafio prático da DIO, com o objetivo de utilizar Inteligência Artificial como ferramenta de aprendizagem ativa, organização de conteúdo e apoio aos estudos.

O tema escolhido foi **Estrutura de Dados em C**, com foco nos principais conceitos estudados na disciplina de Estrutura de Dados II. O projeto utiliza o **NotebookLM** como ferramenta de apoio para leitura dos materiais, criação de resumos, comparação entre conceitos, elaboração de perguntas de revisão e construção de um miniguia de estudo.

A proposta principal foi transformar materiais teóricos em um caderno temático organizado, documentando não apenas o conteúdo estudado, mas também o processo de interação com a IA, os prompts utilizados, as dificuldades encontradas e os aprendizados obtidos.

---

## 1. Contexto e objetivos

Estrutura de Dados é uma área essencial para a formação de qualquer pessoa que deseja trabalhar com desenvolvimento de software, pois ensina como organizar, armazenar, buscar, ordenar e manipular informações de maneira eficiente.

Durante o estudo, foi possível perceber que a escolha correta de uma estrutura de dados pode impactar diretamente o desempenho de um programa. Um mesmo problema pode ser resolvido de várias formas, mas algumas soluções consomem mais memória, exigem mais processamento ou tornam a busca por informações muito mais lenta.

Neste caderno temático, os conteúdos foram organizados a partir de materiais em PDF da disciplina, abrangendo desde fundamentos da linguagem C até estruturas mais avançadas, como listas encadeadas, pilhas, filas, árvores binárias, árvores de busca e tabelas hash.

### Objetivos de estudo

Os principais objetivos deste projeto foram:

* Compreender os fundamentos da linguagem C necessários para implementar estruturas de dados.
* Revisar conceitos de variáveis, arrays, structs, ponteiros, funções e alocação dinâmica.
* Entender como funcionam algoritmos de busca e ordenação.
* Comparar estruturas lineares, como listas encadeadas, pilhas e filas.
* Estudar estruturas não lineares, como árvores binárias e árvores binárias de busca.
* Compreender o funcionamento de tabelas hash e tratamento de colisões.
* Relacionar conceitos teóricos com exemplos práticos e trechos de código.
* Utilizar Engenharia de Prompts para obter respostas mais completas e organizadas com auxílio do NotebookLM.
* Criar um material consolidado de revisão para estudos futuros.

---

## 2. Curadoria de fontes

As fontes utilizadas foram selecionadas a partir dos materiais da disciplina de Estrutura de Dados em C. Os PDFs foram enviados ao NotebookLM para servir como base de consulta, resumo e análise.

Os materiais foram agrupados em blocos temáticos para facilitar a organização do estudo.

### Fontes utilizadas

| Fonte | Arquivo                                           | Assunto principal                                                                            | Relevância                                                                  |
| ----- | ------------------------------------------------- | -------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| 1     | `EDI - 01 - Introdução a C.pdf`                   | Sintaxe básica da linguagem C, variáveis, tipos de dados, operadores, entrada e saída        | Serve como base para compreender qualquer implementação em C                |
| 2     | `EDI - 02 - Loops e Array.pdf`                    | Condicionais, estruturas de repetição e arrays                                               | Introduz o conceito de armazenamento de vários dados em uma única estrutura |
| 3     | `EDI - 03 - Ponteiro.pdf`                         | Ponteiros, endereços de memória, ponteiros e arrays, ponteiro para ponteiro                  | Conteúdo fundamental para estruturas dinâmicas                              |
| 4     | `EDI - 04 - Funções.pdf`                          | Funções, parâmetros, retorno, escopo, passagem por valor, passagem por referência e recursão | Base para modularização e algoritmos recursivos                             |
| 5     | `EDI - 05 - Busca.pdf`                            | Busca sequencial, busca sequencial ordenada e busca binária                                  | Demonstra diferentes formas de localizar dados e comparar eficiência        |
| 6     | `EDI - 06 - Ordenação - 01.pdf`                   | Conceitos de ordenação, SelectionSort, BubbleSort, InsertionSort, estabilidade               | Introduz algoritmos clássicos de ordenação                                  |
| 7     | `EDI - 07 - Ordenação - 02 - TEMPORARIO.pptx.pdf` | MergeSort e divisão para conquistar                                                          | Apresenta um método eficiente e recursivo de ordenação                      |
| 8     | `EDI - 08 - Ordenação - 03.pptx.pdf`              | Ordenação de array de structs                                                                | Aplica ordenação em dados mais próximos de problemas reais                  |
| 9     | `EDI - 09 - Struct + Alocação Dinâmica.pptx.pdf`  | Structs, malloc, calloc, realloc, free e alocação dinâmica                                   | Explica como criar estruturas em tempo de execução                          |
| 10    | `EDI - 10 - Lista Encadeada.pdf`                  | Lista simplesmente encadeada, lista duplamente encadeada, lista com cabeça e lista circular  | Introduz estruturas dinâmicas lineares                                      |
| 11    | `EDI - 11 - Pilha Fila.pdf`                       | Pilhas, filas, LIFO, FIFO, fila circular                                                     | Mostra estruturas com regras específicas de inserção e remoção              |
| 12    | `EDI - 12 - Árvore.pdf`                           | Árvores, árvore binária, árvore binária de busca, percursos, inserção, busca e remoção       | Apresenta estruturas hierárquicas e não lineares                            |
| 13    | `EDI - 14 - Tabela Hash - T.pdf`                  | Tabela hash, função hash, colisões, endereçamento aberto e encadeamento separado             | Mostra técnicas de indexação e busca eficiente                              |

### Critérios de escolha

As fontes foram escolhidas porque representam os principais conteúdos estudados na disciplina e permitem construir uma sequência lógica de aprendizado.

O estudo começa com fundamentos de C, passa por ponteiros, funções e alocação dinâmica, avança para busca e ordenação, depois chega em estruturas lineares e finaliza com árvores e tabelas hash.

Essa ordem foi importante porque os conteúdos se conectam entre si. Ponteiros e alocação dinâmica, por exemplo, são fundamentais para entender listas encadeadas e árvores. Já os algoritmos de busca e ordenação ajudam a compreender por que algumas estruturas são mais eficientes que outras em determinados cenários.

---

## 3. Metodologia de uso do NotebookLM

O NotebookLM foi utilizado como ferramenta de apoio para transformar os PDFs em um material mais organizado e fácil de revisar.

O processo seguiu as seguintes etapas:

1. Upload dos PDFs da disciplina no NotebookLM.
2. Criação de perguntas gerais para identificar o tema central dos materiais.
3. Geração de resumos por assunto.
4. Teste de diferentes prompts para comparar a qualidade das respostas.
5. Solicitação de explicações simples para conceitos difíceis.
6. Criação de tabelas comparativas entre estruturas de dados.
7. Elaboração de um glossário com os principais termos.
8. Organização de um miniguia final de estudo.
9. Registro das dificuldades encontradas durante o uso da IA.

O objetivo não foi apenas pedir respostas prontas, mas usar a IA como apoio para estudar, revisar, comparar e melhorar a compreensão dos conteúdos.

---

## 4. Engenharia de Prompts e cicatrizes

Durante o projeto, foram testados diferentes tipos de prompts para observar como a qualidade da instrução influencia diretamente a qualidade da resposta gerada pela IA.

### Prompt 1 — Pergunta geral

**Prompt utilizado:**

```txt
Explique Estrutura de Dados II de forma geral, como se eu fosse iniciante.
```

**Resultado obtido:**

A resposta ajudou a entender a disciplina de forma ampla, usando analogias simples, como pilha de pratos para pilhas, fila de banco para filas e árvore genealógica para árvores.

**Cicatriz identificada:**

Apesar de ser uma boa introdução, o prompt foi genérico demais. A resposta não organizou todos os conteúdos dos PDFs com profundidade e deixou alguns temas sem detalhamento.

---

### Prompt 2 — Contexto e objetivos

**Prompt utilizado:**

```txt
Com base nos PDFs enviados, explique qual é o tema central do material e quais são os principais objetivos de estudo da disciplina Estrutura de Dados II.
```

**Resultado obtido:**

O NotebookLM identificou que o tema central era a organização, processamento e recuperação eficiente de informações utilizando a linguagem C. Também dividiu os objetivos em fundamentos de C, gestão de memória, busca, ordenação, estruturas dinâmicas, árvores e tabelas hash.

**Cicatriz identificada:**

A resposta foi útil para iniciar o README, mas ainda precisava de adaptação para ficar com linguagem mais acadêmica e organizada.

---

### Prompt 3 — Curadoria de fontes

**Prompt utilizado:**

```txt
Liste as fontes enviadas no NotebookLM, identificando o assunto principal de cada uma e explicando por que cada fonte é relevante para o estudo de Estrutura de Dados II.
```

**Resultado obtido:**

A IA listou os 13 PDFs enviados, identificando o tema principal de cada arquivo e explicando sua importância para a disciplina.

**Cicatriz identificada:**

A resposta ficou boa, mas precisei reorganizar em tabela para deixar o README mais limpo e fácil de ler.

---

### Prompt 4 — Resumo estruturado

**Prompt utilizado:**

```txt
Com base apenas nas fontes enviadas, crie um resumo estruturado de Estrutura de Dados II dividido por assunto, incluindo definição, principais operações, exemplos de aplicação e pontos de atenção para prova.
```

**Resultado obtido:**

Esse foi um dos prompts mais eficientes. A resposta separou o conteúdo em gestão de memória, busca, ordenação, listas, pilhas, filas, árvores e tabela hash.

**Cicatriz identificada:**

Quando o prompt especificou o formato da resposta, a qualidade melhorou bastante. Isso mostrou que prompts claros, com estrutura definida, geram respostas mais úteis.

---

### Prompt 5 — Explicação de códigos

**Prompt utilizado:**

```txt
Explique os principais exemplos de código presentes nas fontes enviadas. Para cada exemplo, diga qual estrutura de dados está sendo usada, qual é a lógica do algoritmo e quais partes do código são mais importantes.
```

**Resultado obtido:**

A IA explicou exemplos de busca sequencial, busca binária, busca em array de structs, MergeSort, InsertionSort em structs, alocação dinâmica e árvore binária de busca.

**Cicatriz identificada:**

A resposta ajudou bastante, mas percebi que, para estudar código, o ideal é pedir explicação por partes: estrutura usada, lógica do algoritmo, variáveis importantes, fluxo de execução e erros comuns.

---

### Prompt 6 — Dificuldades para iniciantes

**Prompt utilizado:**

```txt
Quais partes do conteúdo enviado podem gerar mais dificuldade para um aluno iniciante? Explique os motivos e dê sugestões de estudo para cada dificuldade.
```

**Resultado obtido:**

A IA identificou como pontos mais difíceis: ponteiros, alocação dinâmica, recursão, remoção em listas e árvores, complexidade de algoritmos e colisões em tabelas hash.

**Cicatriz identificada:**

Esse prompt foi importante porque mostrou que estudar apenas o resumo não basta. Alguns temas precisam de desenho, teste de mesa e prática com código.

---

### Prompt 7 — Comparação entre estruturas

**Prompt utilizado:**

```txt
Compare listas, pilhas, filas, árvores, AVL e tabela hash. Mostre diferenças, semelhanças, vantagens, desvantagens e exemplos de uso.
```

**Resultado obtido:**

A resposta comparou estruturas lineares, hierárquicas e de indexação. Também mostrou diferenças de eficiência entre listas, árvores e tabelas hash.

**Cicatriz identificada:**

A comparação foi útil, mas o conteúdo de AVL nos PDFs não estava tão aprofundado quanto os demais. Por isso, neste README, a AVL é tratada como conceito complementar relacionado a árvores balanceadas.

---

### Prompt 8 — Glossário

**Prompt utilizado:**

```txt
Crie um glossário com os principais conceitos encontrados nas fontes enviadas sobre Estrutura de Dados II. Para cada termo, apresente uma definição simples e objetiva.
```

**Resultado obtido:**

A IA criou um glossário com termos como nó, ponteiro, lista encadeada, pilha, fila, árvore, raiz, folha, AVL, fator de balanceamento, rotação, hash, colisão, ordenação e recursão.

**Cicatriz identificada:**

O glossário ajudou a fixar conceitos, mas alguns termos precisaram ser revisados para manter coerência com os PDFs enviados.

---

## 5. Principais cicatrizes do processo

Durante o uso do NotebookLM, ficaram evidentes algumas lições importantes sobre Engenharia de Prompts:

* Prompts genéricos geram respostas genéricas.
* Quando o formato da resposta é especificado, o resultado fica mais organizado.
* Pedir exemplos práticos melhora a compreensão de conceitos abstratos.
* Pedir pontos de atenção para prova ajuda a estudar de forma mais direcionada.
* Para códigos, é melhor pedir explicação por estrutura, lógica, variáveis e erros comuns.
* A IA ajuda muito na organização do estudo, mas as respostas precisam ser revisadas.
* Alguns conteúdos, como AVL, exigem complementação caso o material de origem não esteja detalhado.

---

## 6. Miniguia de estudo

### 6.1 Fundamentos de C

A linguagem C é a base usada nos materiais para implementar as estruturas de dados.

Os principais conceitos revisados foram:

* Variáveis.
* Tipos de dados.
* Operadores.
* Entrada e saída com `printf` e `scanf`.
* Condicionais com `if`, `else` e `switch`.
* Laços de repetição com `for`, `while` e `do-while`.
* Arrays.
* Structs.
* Typedef.

Esses conceitos são importantes porque toda estrutura de dados precisa ser representada no código por meio de variáveis, tipos, funções e blocos de controle.

**Exemplo prático:** um array pode armazenar várias notas de alunos, evitando a criação de uma variável para cada nota.

---

### 6.2 Ponteiros

Ponteiros são variáveis que armazenam endereços de memória.

Eles são fundamentais em C porque permitem acessar e modificar dados indiretamente, além de possibilitar a criação de estruturas dinâmicas.

Principais conceitos:

* `&` retorna o endereço de uma variável.
* `*` acessa o conteúdo apontado por um ponteiro.
* Ponteiros devem ser inicializados antes do uso.
* Ponteiros podem apontar para variáveis, arrays, structs e outros ponteiros.
* Ponteiros e arrays possuem uma relação muito forte em C.

**Exemplo prático:** em uma lista encadeada, cada nó possui um ponteiro para o próximo nó.

**Erro comum:** usar ponteiro sem inicializar. Isso pode fazer o programa acessar uma região indefinida da memória.

---

### 6.3 Funções e recursão

Funções permitem dividir um programa em partes menores e reutilizáveis.

Principais conceitos:

* Funções podem receber parâmetros.
* Funções podem retornar valores.
* Parâmetros podem ser passados por valor ou por referência.
* Arrays são passados para funções como referência.
* Structs podem ser passadas por valor ou por referência.
* Recursão ocorre quando uma função chama a si mesma.

A recursão é muito importante em Estrutura de Dados porque aparece em algoritmos como MergeSort e nos percursos de árvores.

**Exemplo prático:** calcular o fatorial de um número usando uma função recursiva.

**Erro comum:** criar uma função recursiva sem critério de parada, causando chamadas infinitas.

---

### 6.4 Alocação dinâmica

A alocação dinâmica permite reservar memória durante a execução do programa.

Principais funções:

* `malloc`: aloca um bloco de memória.
* `calloc`: aloca memória e inicializa os valores.
* `realloc`: altera o tamanho de um bloco já alocado.
* `free`: libera a memória alocada.
* `sizeof`: informa o tamanho de um tipo em bytes.

Esse conteúdo é fundamental para criar estruturas que crescem conforme a necessidade do programa, como listas encadeadas e árvores.

**Exemplo prático:** criar um array cujo tamanho é informado pelo usuário durante a execução.

**Erro comum:** usar `malloc` e esquecer de usar `free`, causando vazamento de memória.

---

### 6.5 Busca em arrays

Busca é o processo de localizar um elemento dentro de um conjunto de dados.

#### Busca sequencial

Percorre o array do início ao fim, comparando cada posição com o valor procurado.

* Melhor caso: `O(1)`, quando o elemento está na primeira posição.
* Pior caso: `O(N)`, quando o elemento está no final ou não existe.
* Não exige dados ordenados.

#### Busca sequencial ordenada

Também percorre o array sequencialmente, mas aproveita o fato de os dados estarem ordenados para parar antes.

* Exige array ordenado.
* Continua tendo pior caso `O(N)`.
* Pode interromper a busca quando encontra valor maior que o procurado.

#### Busca binária

Divide o array ao meio repetidamente até encontrar o elemento ou concluir que ele não existe.

* Exige array ordenado.
* Melhor caso: `O(1)`.
* Pior caso: `O(log N)`.
* Muito mais eficiente para grandes volumes de dados.

**Ponto de atenção:** não se deve aplicar busca binária em array desordenado.

---

### 6.6 Ordenação

Ordenação é o processo de rearranjar dados em ordem crescente ou decrescente.

A ordenação facilita a recuperação posterior de informações e permite o uso de algoritmos mais eficientes, como a busca binária.

#### SelectionSort

Procura o menor elemento e o coloca na primeira posição, repetindo o processo para o restante do array.

* Simples de entender.
* Poucas movimentações.
* Mesmo no melhor caso, faz muitas comparações.
* Geralmente não é estável.

#### BubbleSort

Compara pares de elementos adjacentes e troca quando estão fora de ordem.

* Simples de implementar.
* Estável.
* Pode ser lento na prática.
* Realiza muitas movimentações.

#### InsertionSort

Insere cada elemento na posição correta em relação aos elementos anteriores já ordenados.

* Estável.
* Bom para conjuntos pequenos ou quase ordenados.
* Lembra a organização de cartas de baralho.

#### MergeSort

Usa a estratégia de dividir para conquistar.

O array é dividido recursivamente até chegar a partes pequenas, depois essas partes são combinadas de forma ordenada.

* Mais eficiente para grandes volumes.
* Complexidade média: `O(N log N)`.
* Usa recursão.
* Precisa de memória auxiliar.

#### Radix Sort e Bucket Sort

São métodos de ordenação por distribuição, ou seja, não dependem apenas de comparações diretas entre elementos.

* Bucket Sort distribui dados em baldes.
* Radix Sort ordena dígito por dígito.
* São úteis quando se conhece bem o formato dos dados.

---

### 6.7 Listas encadeadas

Lista encadeada é uma estrutura dinâmica formada por nós.

Cada nó armazena um dado e um ponteiro para o próximo elemento.

Tipos estudados:

* Lista simplesmente encadeada.
* Lista duplamente encadeada.
* Lista encadeada com cabeça.
* Lista encadeada circular.

#### Vantagens

* Melhor uso da memória.
* Não precisa deslocar elementos como em arrays.
* Cresce conforme a necessidade.

#### Desvantagens

* Acesso indireto.
* Para encontrar um elemento, é necessário percorrer a lista.
* Usa ponteiros, o que aumenta a complexidade do código.

**Exemplo prático:** uma corrente, em que cada elo aponta para o próximo.

---

### 6.8 Pilhas

Pilha é uma estrutura do tipo **LIFO**: Last-In, First-Out.

Isso significa que o último elemento inserido é o primeiro a ser removido.

Principais operações:

* `push`: empilhar.
* `pop`: desempilhar.
* Verificar o topo.
* Verificar se está vazia.
* Verificar se está cheia, no caso de implementação com vetor.

**Exemplo prático:** pilha de pratos. O último prato colocado no topo é o primeiro a ser retirado.

**Aplicações:**

* Recursão.
* Desfazer/refazer em editores.
* Histórico de navegação.

---

### 6.9 Filas

Fila é uma estrutura do tipo **FIFO**: First-In, First-Out.

Isso significa que o primeiro elemento inserido é o primeiro a ser removido.

Principais operações:

* `enqueue`: enfileirar.
* `dequeue`: desenfileirar.
* Verificar o primeiro elemento.
* Verificar se está vazia.
* Verificar se está cheia.

**Exemplo prático:** fila de banco ou fila de impressão.

Em implementações com vetor, é comum utilizar fila circular para evitar desperdício de espaço.

---

### 6.10 Árvores binárias

Árvores são estruturas hierárquicas e não lineares.

Uma árvore binária é uma árvore em que cada nó possui no máximo dois filhos:

* Filho esquerdo.
* Filho direito.

Principais conceitos:

* Raiz: nó principal da árvore.
* Pai: nó que possui filhos.
* Filho: nó abaixo de outro.
* Folha: nó sem filhos.
* Altura: maior caminho da raiz até uma folha.
* Nível: distância entre a raiz e determinado nó.
* Peso: quantidade de nós da árvore.

#### Percursos em árvore

* Pré-ordem: raiz, esquerda, direita.
* Em-ordem: esquerda, raiz, direita.
* Pós-ordem: esquerda, direita, raiz.

**Ponto importante:** em uma árvore binária de busca, o percurso em-ordem retorna os dados em ordem crescente.

---

### 6.11 Árvore Binária de Busca

A Árvore Binária de Busca, também chamada de ABB, é uma árvore binária com regra de organização:

* Valores menores que o nó atual ficam à esquerda.
* Valores maiores que o nó atual ficam à direita.
* Normalmente, não há valores repetidos.

Principais operações:

* Inserção.
* Busca.
* Remoção.

#### Vantagens

* Estrutura dinâmica.
* Inserção mais simples do que em arrays ordenados.
* Busca eficiente quando a árvore está balanceada.

#### Desvantagens

* Pode se tornar degenerada.
* Se os dados forem inseridos já ordenados, a árvore pode ficar parecida com uma lista.
* A remoção de nó com dois filhos exige cuidado.

**Ponto de atenção para prova:** ao remover um nó com dois filhos, é necessário reorganizar a árvore para manter a regra da ABB.

---

### 6.12 Árvores AVL

A Árvore AVL é uma árvore binária de busca auto-balanceada.

Seu objetivo é evitar que a árvore fique muito desbalanceada, mantendo a altura controlada e garantindo melhor desempenho nas operações de busca, inserção e remoção.

Conceitos relacionados:

* Fator de balanceamento.
* Rotação simples.
* Rotação dupla.
* Balanceamento após inserção ou remoção.

Neste projeto, a AVL aparece como conceito complementar, pois os materiais enviados abordam com mais profundidade árvores binárias e árvores binárias de busca.

---

### 6.13 Tabela Hash

Tabela Hash é uma estrutura que busca acesso rápido aos dados.

Ela utiliza uma função de hashing para transformar uma chave em uma posição dentro de um array.

#### Função hash

É responsável por calcular onde um dado deve ser armazenado.

Métodos estudados:

* Método da divisão.
* Método da multiplicação.
* Método da dobra.

#### Colisões

Colisão ocorre quando duas chaves diferentes geram a mesma posição na tabela.

Formas de tratamento:

* Endereçamento aberto.
* Sondagem linear.
* Sondagem quadrática.
* Duplo hash.
* Encadeamento separado.

#### Vantagens

* Busca muito eficiente.
* Caso médio próximo de `O(1)`.
* Boa opção para indexação rápida.

#### Desvantagens

* Pode ter colisões.
* Não é boa para recuperar dados ordenados.
* A escolha da função hash influencia diretamente o desempenho.

**Exemplo prático:** usar a matrícula de um aluno como chave para encontrar rapidamente seus dados.

---

## 7. Comparativo entre estruturas

| Estrutura               | Tipo de acesso           | Vantagem                      | Desvantagem                   | Exemplo                    |
| ----------------------- | ------------------------ | ----------------------------- | ----------------------------- | -------------------------- |
| Array                   | Direto por índice        | Acesso rápido                 | Tamanho fixo                  | Lista de notas             |
| Lista encadeada         | Sequencial por ponteiros | Inserção e remoção flexíveis  | Busca lenta                   | Lista dinâmica             |
| Pilha                   | LIFO                     | Controle simples de histórico | Acesso apenas ao topo         | Desfazer                   |
| Fila                    | FIFO                     | Mantém ordem de chegada       | Acesso restrito               | Fila de impressão          |
| Árvore Binária de Busca | Hierárquico              | Busca eficiente se balanceada | Pode degenerar                | Índice de valores          |
| AVL                     | Hierárquico balanceado   | Mantém busca eficiente        | Implementação mais complexa   | Sistemas com muitas buscas |
| Tabela Hash             | Direto por chave         | Busca média `O(1)`            | Colisões e falta de ordenação | Dicionários e indexação    |

---

## 8. Pontos de atenção para prova

Durante o estudo, alguns pontos apareceram como mais importantes para revisão:

* Busca binária só funciona corretamente em dados ordenados.
* Ponteiros não inicializados podem causar erros graves.
* Todo `malloc` deve ter um `free` correspondente.
* Em C, arrays são passados por referência para funções.
* Recursão precisa obrigatoriamente de critério de parada.
* SelectionSort geralmente não é estável.
* BubbleSort e InsertionSort são estáveis.
* MergeSort usa dividir para conquistar.
* Pilha segue LIFO.
* Fila segue FIFO.
* Lista encadeada não permite acesso direto por índice.
* Em árvores, a altura influencia diretamente o custo das operações.
* Em uma ABB, o percurso em-ordem gera valores ordenados.
* Tabelas hash podem ter colisões.
* Funções hash ruins aumentam o número de colisões.
* Encadeamento separado usa listas para tratar colisões.
* Endereçamento aberto procura outra posição dentro da própria tabela.

---

## 9. Glossário

| Termo                 | Definição                                                | Exemplo                                                   |
| --------------------- | -------------------------------------------------------- | --------------------------------------------------------- |
| Variável              | Espaço de memória que armazena um valor                  | `int idade = 20;`                                         |
| Array                 | Conjunto de elementos do mesmo tipo acessados por índice | `int notas[5];`                                           |
| Struct                | Agrupamento de dados de tipos diferentes                 | Cadastro de aluno com nome, matrícula e nota              |
| Ponteiro              | Variável que armazena endereço de memória                | `int *p;`                                                 |
| `&`                   | Operador que retorna o endereço de uma variável          | `p = &x;`                                                 |
| `*`                   | Operador que acessa o conteúdo apontado                  | `*p = 10;`                                                |
| `malloc`              | Função que aloca memória dinamicamente                   | Criar array em tempo de execução                          |
| `free`                | Função que libera memória alocada                        | Liberar espaço após uso                                   |
| Nó                    | Unidade de uma estrutura encadeada ou árvore             | Nó de lista ou árvore                                     |
| Lista encadeada       | Estrutura formada por nós ligados por ponteiros          | Lista dinâmica de alunos                                  |
| Pilha                 | Estrutura LIFO                                           | Pilha de pratos                                           |
| Fila                  | Estrutura FIFO                                           | Fila de banco                                             |
| Busca sequencial      | Busca elemento por elemento                              | Procurar nome em lista desordenada                        |
| Busca binária         | Busca dividindo o conjunto ao meio                       | Procurar palavra em dicionário                            |
| Ordenação             | Organização dos dados em ordem                           | Ordenar notas em ordem crescente                          |
| Estabilidade          | Manter ordem relativa de elementos iguais                | Ordenar alunos por idade mantendo nomes na ordem original |
| Recursão              | Função que chama a si mesma                              | Fatorial e MergeSort                                      |
| Árvore                | Estrutura hierárquica de nós                             | Pastas de um sistema                                      |
| Raiz                  | Primeiro nó da árvore                                    | Nó principal                                              |
| Folha                 | Nó sem filhos                                            | Arquivo sem subpastas                                     |
| ABB                   | Árvore Binária de Busca                                  | Valores menores à esquerda e maiores à direita            |
| AVL                   | Árvore binária de busca balanceada                       | Árvore que evita degeneração                              |
| Hash                  | Técnica de transformar chave em índice                   | Matrícula gerando posição no array                        |
| Colisão               | Quando duas chaves geram o mesmo índice                  | 255 e 355 em tabela de tamanho 10                         |
| Encadeamento separado | Tratamento de colisão usando listas                      | Lista em cada posição da hash                             |
| Endereçamento aberto  | Tratamento de colisão buscando posição livre na tabela   | Sondagem linear                                           |

---

## 10. Prompts reutilizáveis

Durante o projeto, foram criados prompts que podem ser reutilizados para futuras revisões.

### Resumo por tema

```txt
Explique o tema [TEMA] com base nos materiais enviados, usando linguagem simples, exemplos práticos e tópicos organizados.
```

### Explicação de código

```txt
Explique o código abaixo linha por linha. Diga qual problema ele resolve, quais variáveis são importantes, qual estrutura de dados está sendo usada e quais erros um iniciante poderia cometer.
```

### Comparação entre conceitos

```txt
Compare [CONCEITO A] e [CONCEITO B], mostrando definição, diferenças, semelhanças, vantagens, desvantagens e exemplos.
```

### Revisão para prova

```txt
Monte uma revisão rápida sobre [TEMA], destacando conceitos essenciais, erros comuns e pontos que costumam cair em prova.
```

### Questões de múltipla escolha

```txt
Crie 10 questões de múltipla escolha sobre [TEMA], com gabarito comentado ao final.
```

### Glossário

```txt
Crie um glossário sobre [TEMA], com termo, definição simples e exemplo de uso.
```

### Análise de erro

```txt
Analise o código abaixo, encontre os erros e explique como corrigir.
```

### Explicação para iniciante

```txt
Explique [TEMA] como se eu estivesse aprendendo pela primeira vez, usando analogias e exemplos simples.
```

### Complexidade

```txt
Explique a complexidade de tempo e memória de [ALGORITMO], mostrando melhor caso, pior caso e caso médio quando aplicável.
```

### Estudo guiado

```txt
Crie um plano de estudo de 7 dias para revisar [TEMA], incluindo teoria, prática e exercícios.
```

---

## 11. Estrutura sugerida do repositório

```txt
.
├── README.md
├── fontes/
│   ├── EDI-01-Introducao-a-C.pdf
│   ├── EDI-02-Loops-e-Array.pdf
│   ├── EDI-03-Ponteiro.pdf
│   ├── EDI-04-Funcoes.pdf
│   ├── EDI-05-Busca.pdf
│   ├── EDI-06-Ordenacao-01.pdf
│   ├── EDI-07-Ordenacao-02.pdf
│   ├── EDI-08-Ordenacao-03.pdf
│   ├── EDI-09-Struct-Alocacao-Dinamica.pdf
│   ├── EDI-10-Lista-Encadeada.pdf
│   ├── EDI-11-Pilha-Fila.pdf
│   ├── EDI-12-Arvore.pdf
│   └── EDI-14-Tabela-Hash.pdf
├── prompts/
│   └── prompts-reutilizaveis.md
├── resumos/
│   ├── fundamentos-c.md
│   ├── busca.md
│   ├── ordenacao.md
│   ├── listas-pilhas-filas.md
│   ├── arvores.md
│   └── tabela-hash.md
└── glossario/
    └── glossario-estrutura-de-dados.md
```

---

## 12. Aprendizados finais

Ao desenvolver este caderno temático, percebi que o uso de IA pode tornar o estudo mais ativo, desde que as perguntas sejam bem formuladas.

O NotebookLM ajudou a transformar vários PDFs em um material mais organizado, com resumos, explicações, comparações, glossário e revisão para prova. Porém, o processo também mostrou que a IA não substitui o estudo: é necessário revisar as respostas, conferir os conceitos e testar os códigos.

A maior evolução aconteceu quando os prompts deixaram de ser genéricos e passaram a especificar exatamente o que era esperado: tema, formato, profundidade, exemplos e pontos de atenção.

Este projeto reforçou a importância de Estrutura de Dados para o desenvolvimento de software e mostrou que conceitos como ponteiros, alocação dinâmica, busca, ordenação, listas, pilhas, filas, árvores e tabelas hash são fundamentais para criar programas mais eficientes e bem organizados.

---

## 13. Conclusão

Este repositório representa um caderno temático de estudos sobre **Estrutura de Dados em C**, desenvolvido com apoio do NotebookLM e organizado a partir de materiais acadêmicos da disciplina.

O projeto reúne contexto, objetivos, curadoria de fontes, registros de prompts, dificuldades encontradas, miniguia de estudo, glossário e prompts reutilizáveis.

Mais do que apenas resumir os PDFs, o objetivo foi documentar o processo de aprendizagem com IA, mostrando como a Engenharia de Prompts pode melhorar a qualidade dos estudos e ajudar na construção de materiais mais claros, completos e reutilizáveis.

Link NotebookLM: https://notebooklm.google.com/notebook/772a7c28-1f7d-4f49-8fab-585c8942db92
