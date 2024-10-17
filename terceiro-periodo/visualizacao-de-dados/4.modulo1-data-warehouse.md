# Data Warehouse 📦
Um Data Warehouse (Armazém de Dados) **é um sistema de armazenamento e gerenciamento de grandes volumes de dados, projetado para facilitar a análise e relatórios.** Ele integra dados de múltiplas fontes e os organiza de 
forma otimizada para consultas e decisões estratégicas.

## Características de um Data Warehouse 📄
1. **Orientado por Assunto:** Organiza dados por temas de interesse para o negócio, como vendas, finanças, ou clientes. Isso facilita a análise focada em áreas específicas.

2. **Integrado:** Um Data Warehouse consolida dados de diversas fontes, aplicando processos de padronização para garantir consistência. Dados podem vir de sistemas operacionais, bancos de dados transacionais, planilhas, etc.

3. **Variação Temporal:** Armazena dados históricos, permitindo análises ao longo do tempo. Diferente dos bancos de dados transacionais, que focam em dados atuais, o Data Warehouse preserva dados antigos para comparações
e tendências.

4. **Não Volátil:** Uma vez que os dados entram no Data Warehouse, eles não são alterados ou removidos, apenas adicionados. Isso assegura consistência e confiabilidade nas análises históricas.

## Arquitetura de um Data Warehouse 📐
Um Data Warehouse é composto por várias camadas e processos que garantem a coleta, transformação e acesso aos dados. As principais etapas são:

- **ETL (Extract, Transform, Load):** Processo responsável por extrair dados das fontes, transformá-los em um formato adequado e carregá-los no armazém.
  - Extract: Coleta dados de várias fontes.
  - Transform: Limpa e padroniza os dados, aplicando regras de negócios.
  - Load: Carrega os dados processados no Data Warehouse.

- **Camada de Armazenamento:** É onde os dados são efetivamente armazenados. Eles podem ser organizados em esquemas de estrela (Star Schema) ou floco de neve (Snowflake Schema) para facilitar as consultas.

- **Ferramentas de Acesso:** Os usuários acessam os dados do armazém por meio de ferramentas de BI (Business Intelligence), consultas SQL, dashboards e relatórios que facilitam a visualização e análise dos dados.

<img src="https://i.ibb.co/ckfFrcS/19-07pic01.jpg">

## Vantagens de um Data Warehouse 🆒
1. **Análise Multidimensional:** Oferece suporte a consultas complexas, como agregações, comparações temporais e drill-down, ajudando na tomada de decisões estratégicas.

2. **Desempenho Otimizado:** Por ser otimizado para leitura, o Data Warehouse oferece uma performance significativamente melhor em consultas analíticas comparado aos sistemas transacionais.

3. **Histórico de Dados:** A manutenção de dados históricos permite análises profundas de tendências ao longo do tempo, o que é essencial para planejamento e previsões.

4. **Decisões Baseadas em Dados:** Consolida dados de toda a organização, oferecendo uma visão única e consistente, ideal para gerar insights estratégicos e operacionais.

## Diferença entre Data Warehouse e Banco de Dados Transacional
- Data Warehouse: Focado em análise de dados históricos, com otimização para consultas de leitura e relatórios. Ele armazena dados em um formato desnormalizado (como em Star Schema) para facilitar a leitura rápida.

- Banco de Dados Transacional: Projetado para processar transações rápidas e frequentes (como inserir, atualizar, excluir). São altamente normalizados para evitar redundância de dados, mas não são ideais para
consultas analíticas complexas.

<img src="https://i.ibb.co/Ybb9Vdt/65c55a5c6c2cf5ef105bad6c-image.png">

## Exemplos de Uso de Data Warehouse

- Relatórios Executivos: Empresas utilizam Data Warehouses para gerar relatórios financeiros e de vendas, monitorando o desempenho ao longo do tempo.

- Análise de Tendências: Com dados históricos armazenados, é possível analisar tendências de mercado, comportamento de clientes e projeções futuras.

- Business Intelligence (BI): Ferramentas de BI se conectam ao Data Warehouse para criar dashboards interativos que permitem análises visuais e detalhadas de KPIs (Key Performance Indicators).
