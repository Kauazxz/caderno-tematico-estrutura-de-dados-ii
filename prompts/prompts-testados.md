# Prompts Testados no NotebookLM

Este arquivo registra os principais prompts utilizados durante o projeto, as respostas obtidas de forma resumida e as dificuldades encontradas durante o processo.

---

## Prompt 1 — Explicação geral

**Prompt utilizado:**

```txt
Explique Estrutura de Dados II de forma geral, como se eu fosse iniciante.
```

**Objetivo:**

Obter uma explicação inicial e simples sobre o tema.

**Resultado obtido:**

A resposta apresentou uma visão geral da disciplina, explicando a importância de organizar dados de forma eficiente. Foram usadas analogias simples, como pilha de pratos para pilhas, fila de banco para filas e árvore genealógica para árvores.

**Cicatriz / aprendizado:**

O prompt foi útil para iniciar o estudo, mas ficou genérico. Ele não explorou com profundidade os conteúdos presentes nos PDFs.

---

## Prompt 2 — Tema central e objetivos

**Prompt utilizado:**

```txt
Com base nos PDFs enviados, explique qual é o tema central do material e quais são os principais objetivos de estudo da disciplina Estrutura de Dados II.
```

**Objetivo:**

Identificar o foco principal dos materiais e construir a seção de contexto e objetivos do README.

**Resultado obtido:**

O NotebookLM identificou que o tema central era a organização, processamento e recuperação eficiente de informações utilizando a linguagem C.

**Cicatriz / aprendizado:**

A resposta foi boa, mas precisei adaptar a linguagem para deixá-la mais adequada ao README do projeto.

---

## Prompt 3 — Curadoria de fontes

**Prompt utilizado:**

```txt
Liste as fontes enviadas no NotebookLM, identificando o assunto principal de cada uma e explicando por que cada fonte é relevante para o estudo de Estrutura de Dados II.
```

**Objetivo:**

Organizar os PDFs usados como fontes de estudo.

**Resultado obtido:**

A IA listou os materiais enviados e explicou a importância de cada arquivo, como introdução à linguagem C, ponteiros, funções, busca, ordenação, listas, pilhas, filas, árvores e tabela hash.

**Cicatriz / aprendizado:**

A resposta ficou útil, mas precisei reorganizar as informações em tabela para melhorar a leitura no GitHub.

---

## Prompt 4 — Resumo estruturado

**Prompt utilizado:**

```txt
Com base apenas nas fontes enviadas, crie um resumo estruturado de Estrutura de Dados II dividido por assunto, incluindo definição, principais operações, exemplos de aplicação e pontos de atenção para prova.
```

**Objetivo:**

Gerar uma base para o miniguia de estudo.

**Resultado obtido:**

A resposta separou o conteúdo em tópicos como gestão de memória, busca, ordenação, listas, pilhas, filas, árvores e tabela hash.

**Cicatriz / aprendizado:**

Esse foi um dos melhores prompts. Ao definir o formato da resposta, o resultado ficou mais organizado, completo e adequado para estudo.

---

## Prompt 5 — Explicação de código

**Prompt utilizado:**

```txt
Explique os principais exemplos de código presentes nas fontes enviadas. Para cada exemplo, diga qual estrutura de dados está sendo usada, qual é a lógica do algoritmo e quais partes do código são mais importantes.
```

**Objetivo:**

Relacionar teoria com implementação em linguagem C.

**Resultado obtido:**

A IA explicou exemplos de busca sequencial, busca binária, array de structs, MergeSort, alocação dinâmica e árvore binária de busca.

**Cicatriz / aprendizado:**

Para estudar código, é melhor pedir explicações separadas por: objetivo do código, estrutura usada, variáveis importantes, fluxo de execução e erros comuns.

---

## Prompt 6 — Dificuldades para iniciantes

**Prompt utilizado:**

```txt
Quais partes do conteúdo enviado podem gerar mais dificuldade para um aluno iniciante? Explique os motivos e dê sugestões de estudo para cada dificuldade.
```

**Objetivo:**

Identificar pontos críticos da disciplina.

**Resultado obtido:**

A IA apontou como maiores dificuldades: ponteiros, alocação dinâmica, recursão, remoção em listas e árvores, complexidade de algoritmos e colisões em tabelas hash.

**Cicatriz / aprendizado:**

Esse prompt mostrou que alguns temas precisam ser estudados com desenho, teste de mesa e prática com código.

---

## Prompt 7 — Comparação entre estruturas

**Prompt utilizado:**

```txt
Compare listas, pilhas, filas, árvores, AVL e tabela hash. Mostre diferenças, semelhanças, vantagens, desvantagens e exemplos de uso.
```

**Objetivo:**

Entender quando usar cada estrutura de dados.

**Resultado obtido:**

A resposta comparou estruturas lineares, hierárquicas e de indexação, mostrando diferenças de acesso, vantagens e desvantagens.

**Cicatriz / aprendizado:**

A comparação ajudou bastante, mas o conteúdo de AVL não estava tão aprofundado nas fontes. Por isso, a AVL foi tratada como conceito complementar.

---

## Prompt 8 — Glossário

**Prompt utilizado:**

```txt
Crie um glossário com os principais conceitos encontrados nas fontes enviadas sobre Estrutura de Dados II. Para cada termo, apresente uma definição simples e objetiva.
```

**Objetivo:**

Criar uma seção de consulta rápida para revisão.

**Resultado obtido:**

A IA gerou termos como nó, ponteiro, lista encadeada, pilha, fila, árvore, raiz, folha, hash, colisão, ordenação e recursão.

**Cicatriz / aprendizado:**

O glossário ajudou a fixar conceitos, mas algumas definições precisaram ser revisadas para manter coerência com os PDFs.

---

## Conclusão dos testes

Durante os testes, ficou claro que a qualidade da resposta depende diretamente da qualidade do prompt. Prompts genéricos geram respostas superficiais. Prompts com contexto, formato e objetivo claro geram respostas muito mais úteis para estudo.

As principais estratégias que funcionaram foram:

* Definir o tema com clareza.
* Pedir respostas por tópicos.
* Solicitar exemplos práticos.
* Pedir pontos de atenção para prova.
* Comparar conceitos parecidos.
* Solicitar explicações de código por partes.
* Registrar dificuldades e ajustes feitos durante o processo.
