# Miniguia de Estudo — Estrutura de Dados em C

Este miniguia resume os principais conteúdos estudados no projeto, com foco em revisão rápida, entendimento dos conceitos e preparação para exercícios e provas.

---

## 1. Fundamentos de C

A linguagem C foi usada como base para implementar as estruturas de dados.

Principais conteúdos:

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

---

## 2. Ponteiros

Ponteiros são variáveis que armazenam endereços de memória.

Principais pontos:

* `&` retorna o endereço de uma variável.
* `*` acessa o conteúdo apontado por um ponteiro.
* Ponteiros precisam ser inicializados antes do uso.
* Ponteiros podem apontar para variáveis, arrays, structs e outros ponteiros.
* Ponteiros são fundamentais para listas encadeadas, árvores e alocação dinâmica.

Erro comum:

* Usar ponteiro sem inicializar, causando acesso indevido à memória.

---

## 3. Funções e recursão

Funções permitem dividir o programa em blocos menores e reutilizáveis.

Principais pontos:

* Funções podem receber parâmetros.
* Funções podem retornar valores.
* Parâmetros podem ser passados por valor ou por referência.
* Arrays são passados como referência.
* Structs podem ser passadas por valor ou referência.
* Recursão ocorre quando uma função chama a si mesma.

A recursão é importante em algoritmos como MergeSort e percursos em árvores.

Erro comum:

* Criar função recursiva sem critério de parada.

---

## 4. Alocação dinâmica

A alocação dinâmica permite reservar memória durante a execução do programa.

Principais funções:

* `malloc`: aloca memória.
* `calloc`: aloca e inicializa memória.
* `realloc`: redimensiona um bloco de memória.
* `free`: libera memória.
* `sizeof`: informa o tamanho de um tipo em bytes.

A alocação dinâmica é fundamental para criar estruturas que crescem conforme a necessidade, como listas e árvores.

Erro comum:

* Usar `malloc` e esquecer de usar `free`.

---

## 5. Busca em arrays

Busca é o processo de localizar um elemento dentro de um conjunto de dados.

### Busca sequencial

Percorre o array do início ao fim.

* Não exige ordenação.
* Melhor caso: `O(1)`.
* Pior caso: `O(N)`.

### Busca sequencial ordenada

Percorre o array, mas para antes quando percebe que o elemento não pode mais aparecer.

* Exige array ordenado.
* Pior caso: `O(N)`.

### Busca binária

Divide o array ao meio repetidamente.

* Exige array ordenado.
* Melhor caso: `O(1)`.
* Pior caso: `O(log N)`.

Ponto de atenção:

* Busca binária não deve ser usada em array desordenado.

---

## 6. Ordenação

Ordenação é o processo de organizar dados em ordem crescente ou decrescente.

### SelectionSort

Seleciona o menor elemento e coloca na posição correta.

* Simples.
* Poucas trocas.
* Muitas comparações.
* Geralmente não é estável.

### BubbleSort

Compara elementos vizinhos e troca quando estão fora de ordem.

* Simples.
* Estável.
* Lento para grandes quantidades de dados.

### InsertionSort

Insere cada elemento na posição correta entre os anteriores já ordenados.

* Estável.
* Bom para listas pequenas ou quase ordenadas.

### MergeSort

Divide o array em partes menores e depois combina tudo em ordem.

* Usa recursão.
* Usa dividir para conquistar.
* Mais eficiente para grandes volumes.
* Complexidade: `O(N log N)`.

### Radix Sort e Bucket Sort

São métodos de ordenação por distribuição.

* Bucket Sort distribui dados em baldes.
* Radix Sort ordena dígito por dígito.

---

## 7. Listas encadeadas

Lista encadeada é uma estrutura dinâmica formada por nós.

Cada nó possui:

* Um dado.
* Um ponteiro para o próximo nó.

Tipos estudados:

* Lista simplesmente encadeada.
* Lista duplamente encadeada.
* Lista com cabeça.
* Lista circular.

Vantagens:

* Cresce conforme a necessidade.
* Inserções e remoções são mais flexíveis.
* Não exige deslocamento de elementos como arrays.

Desvantagens:

* Não possui acesso direto por índice.
* Precisa percorrer a lista para buscar elementos.
* Exige cuidado com ponteiros.

---

## 8. Pilhas

Pilha é uma estrutura do tipo **LIFO**: Last-In, First-Out.

Isso significa que o último elemento inserido é o primeiro a ser removido.

Operações principais:

* `push`: empilhar.
* `pop`: desempilhar.
* Verificar o topo.
* Verificar se está vazia.
* Verificar se está cheia.

Exemplos de uso:

* Desfazer/refazer.
* Recursão.
* Histórico de navegação.

---

## 9. Filas

Fila é uma estrutura do tipo **FIFO**: First-In, First-Out.

Isso significa que o primeiro elemento inserido é o primeiro a ser removido.

Operações principais:

* `enqueue`: enfileirar.
* `dequeue`: desenfileirar.
* Verificar o primeiro elemento.
* Verificar se está vazia.
* Verificar se está cheia.

Exemplos de uso:

* Fila de banco.
* Fila de impressão.
* Troca de mensagens em rede.

Ponto importante:

* Em implementações com vetor, a fila circular ajuda a reaproveitar espaços.

---

## 10. Árvores binárias

Árvore é uma estrutura hierárquica e não linear.

Uma árvore binária é uma árvore em que cada nó possui no máximo dois filhos:

* Filho esquerdo.
* Filho direito.

Conceitos importantes:

* Raiz.
* Pai.
* Filho.
* Folha.
* Altura.
* Nível.
* Peso.

Percursos principais:

* Pré-ordem: raiz, esquerda, direita.
* Em-ordem: esquerda, raiz, direita.
* Pós-ordem: esquerda, direita, raiz.

---

## 11. Árvore Binária de Busca

A Árvore Binária de Busca, ou ABB, segue uma regra:

* Valores menores ficam à esquerda.
* Valores maiores ficam à direita.

Operações principais:

* Inserção.
* Busca.
* Remoção.

Vantagens:

* Estrutura dinâmica.
* Pode ter busca eficiente.
* Facilita inserção em comparação com array ordenado.

Desvantagens:

* Pode ficar degenerada.
* Se os dados forem inseridos em ordem, a árvore pode virar praticamente uma lista.

Ponto de atenção:

* O percurso em-ordem em uma ABB retorna os valores em ordem crescente.

---

## 12. Árvore AVL

A Árvore AVL é uma árvore binária de busca balanceada.

Ela evita que a árvore fique muito desbalanceada, mantendo a altura controlada.

Conceitos relacionados:

* Fator de balanceamento.
* Rotação simples.
* Rotação dupla.

Neste projeto, a AVL foi tratada como conceito complementar, pois os materiais abordam com mais profundidade árvores binárias e árvores binárias de busca.

---

## 13. Tabela Hash

Tabela Hash é uma estrutura usada para acesso rápido aos dados.

Ela utiliza uma função hash para transformar uma chave em uma posição do array.

Conceitos importantes:

* Função hash.
* Chave.
* Índice.
* Colisão.
* Endereçamento aberto.
* Sondagem linear.
* Sondagem quadrática.
* Duplo hash.
* Encadeamento separado.

Vantagens:

* Busca média próxima de `O(1)`.
* Muito útil para indexação rápida.

Desvantagens:

* Pode ter colisões.
* Não é ideal para recuperar dados ordenados.
* Depende de uma boa função hash.

---

## Pontos importantes para prova

* Busca binária exige dados ordenados.
* Ponteiros precisam ser inicializados.
* Todo `malloc` deve ter um `free`.
* Recursão precisa de critério de parada.
* Pilha segue LIFO.
* Fila segue FIFO.
* Lista encadeada não tem acesso direto por índice.
* Em ABB, menores ficam à esquerda e maiores à direita.
* Percurso em-ordem em ABB gera valores ordenados.
* Tabela hash pode ter colisões.
* Encadeamento separado usa listas para tratar colisões.
* Endereçamento aberto procura outra posição dentro da própria tabela.

---

## Conclusão

O estudo de Estrutura de Dados em C mostra como organizar informações de maneira eficiente, escolhendo a estrutura mais adequada para cada problema.

Compreender ponteiros, alocação dinâmica, busca, ordenação, listas, pilhas, filas, árvores e tabelas hash é essencial para desenvolver programas mais rápidos, organizados e com melhor uso de memória.
