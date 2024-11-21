# **Trabalho Prático do Período**
O trabalho prático da matéria de mineração de dados consiste em realizar todo um pré-processamento adequado da Pesquisa Nacional de Saúde do Brasil do ano de 2019 (PNS 2019). Essa base de dados
é um questionário aplicado para vários cidadãos do Brasil e é um tipo de questionário descritivo e não clínico. Então o entrevistado responde o que mais se adequa à ele ou não. Um dos problemas
dessa base de dados é a quantidade massiva de dados nulos, oque torna ainda mais desafiador desenvolver esse projeto.

- link para a base de dados oficial: *https://www.ibge.gov.br/estatisticas/sociais/saude/9160-pesquisa-nacional-de-saude.html?=&t=downloads*

A base contém por volta de 273 mil registros, cada um com 1.087 atributos.

## **Definição do Domínio do Problema**
Para abordar esse trabalho, foi proposto uma abordagem de multiclasse, ao todo 3 classes no problema. **Para o meu caso individual**, estou trabalhando com pessoas "saudáveis", um termo melhor
para essas pessoas são as pessoas que não receberam o diagnóstico das doenças. Em seguida temos as pessoas hipertensas e por último pessoas hipertensas com problemas cardiovasculares. Portanto,
há 3 classes possíveis para uma instância que são essas supracitadas.

Além disso, foi preciso estudar literaturas da área médica e trabalhos relacionados para realizar uma redução de dimensionalidade conceitual, de 1.088 atributos escolher aqueles que melhor
representam o problema definido, não só isso, mas também obtive ajuda de profissionais da área da saúde, como médicos, que forneceram conhecimentos tácitos ou também chamados de *know-how*.

Após a construção de um mapa conceitual para a seleção dos atributos, inicia-se a etapa do projeto de Pré-processamento dos dados.
