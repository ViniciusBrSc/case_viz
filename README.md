# Visualizando dados com o pacote basedosdados

Utilizando o Python na versão 3.7.9 em ambiente virtual controlado, foi possível instalar o pacote `basedosdados`, a fim de baixar a tabela referente aos dados das bolsas da CAPES. 

Também foi feita uma query simples em SQL para filtrar as colunas já no momento do download, selecionando apenas as que faziam sentido para os objetivos da visualização.

Então, depois de um breve tratamento dos dados, foram exploradas 3 visualizações utilizando Plotly e Seaborn em um Jupyter Notebook no VS Code:

1. Os 5 Principais Programas da CAPES em Porcentagem do Total de Bolsas Concedidas.

    1.1 Barplot horizontal interativo.

2. O Investimento da CAPES por Grande Área de Conhecimento ao Longo do Tempo.
    
    2.1 Lineplot interativo (a cada mês).

    2.2 Barplot vertical interativo (a cada ano).

3. Correlações entre os Investimentos de Cada Área.

    3.1 Pairplot.

    3.2 Matriz de Correlações.

    3.3 Scatterplot interativo: Gráfico de Dispersão entre Investimentos em Engenharia e Ciências Exatas e da Terra.

O arquivo `data_visualization.ipynb` encontra-se na pasta `code`, juntamente com o `data_download.ipynb` que foi utilizado para acessar as tabelas remotamente e salvar os dataframes em arquivos pickle comprimidos para garantir tamanhos pequenos.



## Contato: 


Vinicius Branco Scortegagna

viniciusbranco.ufrgs@gmail.com

https://www.linkedin.com/in/vinicius-br-sc/
