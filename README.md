# Caderno Temático: Dominando o Power BI com NotebookLM 📊

## 1. Contexto e Objetivos
Este repositório foi criado como parte do desafio de projeto da DIO "Treinando uma IA de Aprendizagem". O objetivo principal é consolidar meus estudos sobre o *Power BI*, focando em Business Intelligence (BI), modelagem de dados e criação de dashboards de alto impacto. Utilizei o NotebookLM como meu parceiro de estudos para sintetizar conceitos complexos e extrair insights rápidos.

---

## 2. Curadoria de Fontes
Para alimentar o NotebookLM e garantir um aprendizado de qualidade, foram selecionadas as seguintes fontes públicas e oficiais:
* *Fonte 1:* [Documentação Oficial do Power BI - Microsoft](https://learn.microsoft.com/pt-br/power-bi/) (Conceitos de arquitetura e segurança)
* *Fonte 2:* [Guia do Usuário: Linguagem DAX - Microsoft](https://learn.microsoft.com/pt-br/dax/) (Sintaxe e funções calculadas)
* *Fonte 3:* Artigo Técnico: Best Practices para Modelagem de Dados em Estrela (Star Schema) - Blog Microsoft.

---

## 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante a interação com o NotebookLM, testei diferentes abordagens de comandos para extrair as melhores explicações sobre Power BI.

### Prompts Testados:
* *Prompt Inicial (Muito vago):* "Me explica o que é DAX."
  * Resultado: A IA trouxe uma resposta genérica e muito teórica.
* *Prompt Refinado (Melhorado):* "Você é um especialista em Power BI. Explique a diferença prática entre uma Coluna Calculada e uma Medida em DAX, dando um exemplo de quando usar cada uma."
  * Resultado: Resposta perfeita, dividida em tópicos e com exemplos claros de performance.

### Cicatrizes (O que deu errado e como corrigi):
* *O problema:* Ao perguntar sobre "relacionamentos", a IA misturou conceitos de SQL tradicional com a modelagem do Power BI.
* *A solução:* Tive que restringir o escopo da pergunta, reformulando para: "Explicique o relacionamento de 1 para muitos (1:N) especificamente dentro do contexto de direção do filtro cruzado no Power BI". Isso corrigiu a alucinação e trouxe a resposta exata.

---

## 4. Miniguia de Estudo (Entrega Final)

### Resumo dos Principais Conceitos
O Power BI é dividido em três pilares fundamentais para transformar dados brutos em decisões:
1. *Power Query (ETL):* Extração, Transformação e Carregamento. É onde limpamos os dados (removemos nulos, alteramos tipos de dados).
2. *Modelagem (DAX):* Onde criamos as relações entre as tabelas (Fatos e Dimensões) e escrevemos fórmulas matemáticas para análises inteligentes.
3. *Visualização:* A criação dos relatórios visuais com gráficos de barras, linhas, mapas e segmentadores de dados.

### Glossário de Termos Técnicos
* *Tabela Fato:* Tabela que armazena os eventos históricos ou quantitativos (Ex: Histórico de Vendas, quantidade de itens vendidos).
* *Tabela Dimensão:* Tabela que traz as características ou atributos dos dados (Ex: Nome do cliente, categoria do produto, data).
* *Medida DAX:* Cálculos dinâmicos que não ocupam espaço na memória do modelo e são calculados no momento em que você clica no gráfico (Contexto de Filtro).
* *Contexto de Linha:* Avaliação linha por linha em uma tabela, muito comum em colunas calculadas.

### Prompts Reutilizáveis para Estudo de Power BI
Você pode copiar os prompts abaixo e colar no seu NotebookLM ou ChatGPT para continuar estudando:
1. "Atue como um analista de BI e me dê 5 ideias de KPIs essenciais para um dashboard de Logística/Supply Chain."
2. "Estou recebendo o erro de 'dependência circular' no Power BI ao tentar criar uma relação. O que isso significa e como posso resolver?"
3. "Crie um plano de estudos passo a passo para eu aprender funções de inteligência de tempo (Time Intelligence) em DAX."
