# Modelagem Multidimensional
A Modelagem Multidimensional é uma abordagem usada em **Data Warehouses e sistemas de Business Intelligence (BI) para organizar dados de forma a facilitar a análise e relatórios.** Ela é projetada para otimizar consultas 
complexas, oferecendo uma visão mais intuitiva e compreensível dos dados, geralmente organizada em dimensões e fatos.

## Componentes da Modelagem Multidimensional
- **Fato:** Representa os eventos ou transações, como vendas ou lucros. A tabela de fatos contém medidas numéricas (como quantidade vendida ou receita) e chaves estrangeiras que se relacionam com as dimensões.

- **Dimensões:** Fornecem o contexto para as tabelas de fatos, como cliente, tempo ou produto. As dimensões armazenam informações descritivas, permitindo que as medidas sejam analisadas em diferentes perspectivas.

## Star Schema (Esquema Estrela) ⭐
O Star Schema é o modelo mais simples e amplamente utilizado na modelagem multidimensional. Ele organiza os dados com uma tabela de fatos central cercada por tabelas de dimensões, formando uma estrutura semelhante a uma 
estrela.

### Organização:

- Tabela de Fatos: No centro, contém as medidas (como valores de vendas, lucro) e as chaves estrangeiras que se relacionam com as dimensões.
- Tabelas de Dimensões: Cada tabela de dimensão está diretamente conectada à tabela de fatos. Exemplos comuns incluem:

**Exemplo:**
- Dimensão Tempo: Anos, meses, dias.
- Dimensão Produto: Nome, categoria, marca.
- Dimensão Cliente: Nome, localização, faixa etária.

O principal benefício do Star Schema é sua simplicidade e eficiência na realização de consultas. Ele facilita a leitura dos dados por parte dos analistas, pois as relações entre as tabelas são claras e diretas.

**Exemplo Contextualizado de Star Schema:**

- Tabela de Fatos: Fato_Vendas (contendo id_produto, id_tempo, id_cliente e medidas como quantidade, valor_venda).
- Tabelas de Dimensões: Dim_Produto, Dim_Tempo, Dim_Cliente.

## Snowflake Lookup (Pesquisa) ❄️
O conceito de Lookup refere-se ao processo de recuperar dados relevantes de uma tabela de dimensões durante a consulta de uma tabela de fatos. Através de chaves estrangeiras, o banco de dados faz "lookups" para obter 
descrições detalhadas ou atributos armazenados nas dimensões.

Por exemplo, se você está analisando as vendas de um produto (id_produto), a consulta realiza um lookup na dimensão Dim_Produto para obter o nome, categoria, e outras características do produto. O lookup é uma prática 
comum para unir dados armazenados em diferentes tabelas, proporcionando a informação contextual necessária para relatórios e análises.

## Snowflake Chain (Cadeia) ❄️
Chain refere-se à modelagem de relacionamentos mais complexos entre tabelas de dimensões e fatos. Ao contrário do esquema estrela, que é simples e direto, um Chain é usado quando há dependências ou relações indiretas 
entre dimensões, muitas vezes levando a estruturas de Snowflake (Esquema Floco de Neve).

No Snowflake Schema, as dimensões são normalizadas em várias tabelas, criando "cadeias" de relações. As dimensões que seriam simples no Star Schema, como produto ou tempo, são divididas em subdimensões.**O propósito da
chain, além de normalizar, é realizar uma análise focada em diferentes tipos de granularidade dos dados.** ❗

**Exemplo de Chain:**

Uma dimensão de produto pode ser dividida em Dim_Produto, Dim_Categoria_Produto, e Dim_Marca_Produto, criando uma cadeia de dependências entre as tabelas.
❗**Essa abordagem pode aumentar a complexidade da consulta** ❗, pois há mais junções (joins) entre tabelas, mas melhora a eficiência no armazenamento, eliminando redundâncias.


## Comparação Star Schema x Snowflake Schema

<img src="https://i.ibb.co/XL70rzm/1699530165218.png">

- Star Schema: Menos junções, mais simples, melhor performance para leitura e análise, mas com certa redundância de dados.
- Snowflake Schema: Mais junções, maior complexidade, melhor normalização dos dados, mas pode ser menos eficiente para consultas complexas.

## Conclusão
A Modelagem Multidimensional permite uma visão estruturada dos dados, ideal para análise em data warehouses. O Star Schema é excelente para consultas rápidas e simples, enquanto abordagens como Lookup e Chain 
proporcionam flexibilidade para modelagens mais complexas, como o Snowflake Schema, onde a eficiência do armazenamento é priorizada.
