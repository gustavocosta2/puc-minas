# **Integração de Dados - Aula 22/08/2024**

## **TEMA: Definições, Requisitos, Características, Razões de Desafios**

### **💡 I. Definições:**
- Integração de Dados é um **processo**, em outras palavras, é uma série de etapas lógicas para combinar os dados de múltiplas fontes, diferentes formatos e armazená-los em um repositório de destino. Dessa forma os dados
ficarão acessíveis para as aplicações de tomada de decisão e/ou para projetos de dados.<br>

- Dados -> Insights -> Tomadas de decisões estratégicas.<br>

- **Replicação de Dados:** é um **backup**, você não altera os dados, você apenas replica os dados para outros servidores, aplicações, etc.<br>

- **Migração de Dados:** é você retirar fisicamente um dado de um local (um banco de dados por exemplo) e passar para outro local, o dado **deixará de existir onde ele estava antes.** É migração ao pé da letra mesmo.<br>

- **Integração de Dados:** é o processo de mover diferentes conjuntos de dados de banco de dados, plataformas de nuvem, e outras fontes para um repositório de dados centralizado.<br>

- **Fontes de dados:** são os locais onde os dados estão armazenados, contendo dados úteis que podem contribuir para a tomada de decisão e gerar algum tipo de **inteligência**.<br>

- **Tipos de fontes de dados:** Podem ser vários, entre eles: arquivos de texto, planilhas eletrônicas, conexões com BDs, arquivos .csv, .json e .xml, APIs de integração, etc.<br>

### **🧾 II. Requisitos:**

A identificação dos requisitos da integração de dados é uma etapa muito importante, porque será esse passo do processo que o resto será construído. Isso inclui:

- Entendimento das fontes de dados.<br>

- Mapeamento dos sistemas informatizados, que incluem os BDs transacionais (OLTP) que mantêm os dados gerados e manipulados pelas aplicações do negócio.<br>

- Mapeamento de Data Warehouse (DW), Data Mart (DM) e Data Lakes.<br>

- Definir a **periodicidade da extração dos dados** ou se o processo será executado de forma permanente (on-line).<br>

- Se for um contexto de integração em larga escala ou também conhecido como Big Data, é necessário dimensionar o sistema para suportar o grande volume de dados.<br>

- (**Importante**) monitorar constantemente o surgimento de novas necessidades para os negócios e novos requisitos de integração que podem surgir.<br>




