# **Aula - Integração de Dados - 28/08/2024**

## **TEMA: Definições, Requisitos, Características, Razões de Desafios (continuação)**

### **🧬 III. Características:**

- Uso de processos técnicos e de negócios para combinar dados de diversas fontes, com o objetivo de **fornecer informação útil e valiosa, de forma eficiente**<br>

- Colaboração entre usuários internos e externos à organização. É a troca de informação para que o objetivo final seja atingido.<br>

- Os dados devem estar disponíveis e acessíveis a partir de uma localização central (Data Mart, DW, Data Lake). A ideia por trás dessa afirmação, é que após você integrar os dados em um repositório central, esses dados
  integrados passam a ser os dados considerados como **verdades** do negócio. Isso implica na sua disponibilidade sempre, para que possa haver o processo de tomadas de decisão.<br>

- Quando uma organização integra seus dados, o tempo para preparar e analisar os dados DEVE ser reduzido significativamente.<br>

### **🆒 IV. Razões:**

Porque integrar os dados? Qual a razão para mobilizar as empresas e realizar esse processo?

- Dados integrados reduzem erros e retrabalho. Isso quer dizer que os dados integrados já passaram por todo o processo de extração, transformação e estão prontos para o uso devidamente correto. Isso acaba sendo uma
otimização de tempo.<br>

- A integração de dados melhora, significativamente, a qualidade dos dados de uma organização porque, mais uma vez, eles ficam concisos.<br>

- A integração de dados permite que uma organização faça mais, usando menos recursos.<br>


### **⚠️ V. Desafios:**

- Unificar diferentes fontes de dados e combiná-las em uma estrutura simples pode ser um processo **bastante difícil**.

- As organizações devem criar processos para mover e traduzir os dados que ainda não estão integrados.

- Fontes de dados externas correm o risco de possuirem **baixa qualidade dos dados, questões de privacidade dos dados que impedem de serem utilizados, etc**.

- Sistemas legados exigem maior esforço devido às características destes sistemas.

- Sistemas de "ponta" que fornecem dados não estruturados e em tempo real (dispositivos IoT, sensores, nuvem, áudio, vídeo) tornam o processamento desses dados mais **díficil**.

- Manter o sistema de integração de acordo com as novas demandas e mudanças de necessidades da organização.

### **🔬 VI. Métodos:**

- **Integração de dados manual:** é o processo de coletar manualmente os dados necessários de diversas fontes, os acessando diretamente.

- **Integração baseada em aplicação:** usa aplicações de software para localizar, recuperar e integrar os dados. É utilizar um *middleware*, ou seja, uma API de integração de dados que age como um mediador e ajuda a
normalizar os dados antes de trazê-los para o *pool* de dados mestres (repositório central).

- **Integração de armazenamento comum:** É a abordagem mais popular de integração e dados, utiliza um repositório central para armazenar os dados integrados.
