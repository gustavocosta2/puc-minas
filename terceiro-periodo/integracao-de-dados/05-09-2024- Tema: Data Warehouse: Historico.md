**Aula - Integração de Dados - 05/09/2024**

# **DATA WAREHOUSE: HISTÓRICO**

O nome Data Warehouse foi dado por William H. Inmon que é considerado o pai dessa tecnologia.

## **4 Características Essenciais de um DW:**

**1. Não volátil ->** os dados devem perdurar no DW.<br>
**2. Orientado por Assunto ->** O DW organiza os dados em torno de áreas específicas do negócio (ex: vendas, finanças), facilitando a análise focada em cada tema.<br>
**3. Variável com o tempo ->** O DW armazena dados históricos, permitindo o acompanhamento de mudanças e tendências ao longo do tempo.<br>
**4. Integrado ->** Os dados no DW são consolidados e padronizados de várias fontes, garantindo consistência e coerência entre os diferentes sistemas.<br>


## **Implementação de Data Marts:**

**-> Top-Down:** é quando uma empresa cria um DW e depois divide-os em Data Marts gerando pequenos bancos orientados por assuntos ou departamentos específicos da empresa.

**-> Bottom-Up:** é quando a empresa inicia um Data Mart e expande o projeto para outras áreas.

A Modelagem Multidimensional é a que está presente em um DW e é estruturada como um CUBO, transmitindo a ideia de múltiplas dimensões, mas vale ressaltar que um cubo é 
tridimensional e em alguns contextos haverá mais dimensões do que apenas 3.
