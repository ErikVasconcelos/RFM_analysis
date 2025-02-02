# RFM_analysis

<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" width="75px" height="22px" alt="python"/>

<p><img src="https://yt3.googleusercontent.com/jbrVFrorma-qy6MktExlP4IcwywfEkDJfBNJvdFiKDDCitUb0L4JlejlGg7aKr0UyRM1i7ve8HA=w1060-fcrop64=1,00005a57ffffa5a8-k-c0xffffffff-no-nd-rj" width="1020px" alt="html-icon"/>

## Extração e Tratamento de Dados em Python (Matéria 5) - Desafio 5 - Análise do RFM dos clientes de uma empresa de Marketing

### **Contexto**

Uma empresa do ramo de e-commerce solicitou um levantamento sobre os indicadores de recência, frequência e ticket médio (RFM) dos seus clientes.

A saber RFM:

- R (Recency): Tempo que o cliente realizou a última compra (em dias)
- F (Frequency): Quantidade de compras realizadas pelo cliente
- M (Monetary): Valor do ticket médio gasto pelo cliente

Ticket médio = média do total gasto por pedido para cada cliente.

Para isso,a empresa disponiblizou uma base de dados (arquivo csv). Inicialmente, foi identificado o Python como ferramenta de utilização, gerando um output seguro e satisfatório para o cliente. Para a segurança da empresa, o arquivo será nomeado contendo apenas a identificação do cliente e métricas RFM.

### Sobre os dados

A tabela contém informações de compras de um e-commerce em 37 países. Contém a identificação do cliente e os dados da compra.

| **Coluna** | **Descrição** |
| --- | --- |
| **CustomerID** | **Código de identificação do cliente** |
| **Description** | **Descrição do produto** |
| **InvoiceNo** | **Código da fatura** |
| **StockCode** | **Código de estoque do produto** |
| **Quantity** | **Quantidade do produto** |
| **InvoiceDate** | **Data do faturamento (compra)** |
| **UnitPrice** | **Preço unitário do produto** |
| **Country** | **País da compra** |

### **Como começar?**

1. Importar o dataset para o colab
2. Entender os dados
3. Tratar os dados nulos
4. Tratar os outliers

Dessa forma, vamos desenvolver o algoritmo para receber o arquivo csv de entrada e retornar um algoritmo de saída com as seguintes colunas:

- **CustomerID: Código do cliente**
- **R: Recência**
- **F: Frequência**
- **M: Ticket médio**
