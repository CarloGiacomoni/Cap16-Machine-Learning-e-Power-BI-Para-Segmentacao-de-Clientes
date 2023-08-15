# Projeto de Segmentação de Clientes utilizando K-Means - Uso de Machine Learning no Power BI.

## Uso de Machine Learning no Power BI para Segmentação de Clientes- Cap 16 do curso de Power BI da DSA (Data Science Academy).

Este projeto visa segmentar os clientes de uma empresa com base em dados históricos de compras, permitindo uma personalização mais eficaz das campanhas de marketing.  
Utilizando Python, implementamos o algoritmo K-Means para realizar a segmentação.

## Descrição do Projeto  
A empresa possui dados históricos de clientes, incluindo as seguintes informações para cada cliente:

- Idade
- Renda Anual
- Pontuação de Gasto (Poder de Compra do Cliente)

O objetivo principal é agrupar os clientes em três segmentos distintos com base em suas similaridades nesses atributos. A segmentação permitirá que a equipe de marketing personalize suas estratégias de maneira mais eficaz, direcionando suas campanhas para públicos-alvo específicos.

## Pré-requisitos

Para este projeto usei:
**Python 3.9.13**
**Bibliotecas: scikit-learn, pandas, matplotlib, powerbiclient 3.1.0**

## Resultados

Após a execução do script, foi gerado um relatório com os três segmentos de clientes, juntamente com a média de idade, renda anual e pontuação de gastos para cada segmento.

## Notas  

Certifique-se de fornecer os dados fictícios corretos no formato apropriado no arquivo dados_clientes.csv.
O número de clusters (segmentos) no algoritmo K-Means pode ser ajustado no código conforme necessário para atender aos requisitos da empresa.  
Este projeto é um exemplo fictício com dados simulados. Certifique-se de substituir os dados e detalhes reais, caso aplique em um cenário real.  
Lembre-se que por padrão o Power BI soma as bases de dados nos visuais.  
É obrigação do analista ficar atento a esta particularidade e fazer os ajustes necessários conforme a necessidade do projeto.  
Para este projeto fiz a partir deste Jupyter notebook a publicação dele no Power BI Service, e posteriormente o Download para o PB desktop para fazer os ajustes, incluir as médias como o projeto exigia.

#### Você pode ver este projeto em meu portfolio de projetos no Power BI, "Dashboard - Segmentação de Clientes", 
neste link: https://sites.google.com/view/portfoliocarlogiacomoni

## Autor:
**Carlo Giacomoni** sob orientação de Data Science Academy para o curso de Microsoft Power BI 
https://www.linkedin.com/in/carlo-giacomoni/
