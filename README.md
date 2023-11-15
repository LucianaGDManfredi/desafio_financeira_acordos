<div align="center">
<h1>Desafio <br> Business Intelligence com Python e Power BI</h1>
<img src="https://www.freecodecamp.org/news/content/images/2022/08/Python-Power-BI-1.png" alt="Logo Pyhton e Power BI" width="220">
</div>

##  :brain: Desafio Original DIO: Explorando IA Generativa em um Pipeline de ETL com Python
Notebook do desafio original resolvido pelo Venilton da DIO:
<a target="_blank" href="https://colab.research.google.com/drive/1SF_Q3AybFPozCcoFBptDSFbMk-6IVGF-?usp=sharing#scrollTo=k5fA5OrXt1a3">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## :rocket: Entendendo o Desafio
Inspirado pelo projeto modelo o aluno deveria replicar ou reimaginar uma pipeline ETL utilizando Python.

## :bar_chart: Meu Projeto 
Supondo que sou a Cientista de Dados de uma empresa de prestações de serviços, criei um pipeline ETL para extrair os dados de dois arquivos CSV e um excel, à saber:
- CadastroFuncionarios;
- CadastroClientes;
- BaseServiçosPrestados.

Em seguida, fiz as transformações  para fazer cálculos para os Indicadores de Performance para a empresa (KPIs).


## :technologist: Etapas do Pipeline de ETL
### :white_check_mark: Extract
Nesta etapa vamos extrair os dados usando a biblioteca Pandas para os seguintes arquivos:  `CadastroClientes.csv` , `CadastroFuncionarios.csv` ,`BaseServiçosPrestados.xlsx`. 
Estes arquivos contem dados para fazer os cálculos do desempenho anual da empresa.


### :white_check_mark: Transform
Agora vamos calcular:
- Valor Total da Folha Salarial: Total de gastos com salários de funcionários pela empresa (salário + benefícios + impostos);
- Faturamento da Empresa;
- Faturamento Médio Mensal;
- Percentual de Funcionários que Já Fechou Contrato;
- Total de Contratos que Cada Área da Empresa já Fechou;
- Total de Funcionários por Área.

### :white_check_mark: Load
 Salvando os dados transformados em um novo arquivo Word e gerando gráficos usando a biblioteca `Matplotlib`.
 

## :battery: Stacks Utilizadas
![VSCODE](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC.svg?style=for-the-badge&logo=Visual-Studio-Code&logoColor=white)
![PYTHON](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![GIT](https://img.shields.io/badge/Git-F05032.svg?style=for-the-badge&logo=Git&logoColor=white)
![GOOGLE COLAB](https://img.shields.io/badge/Google%20Colab-F9AB00.svg?style=for-the-badge&logo=Google-Colab&logoColor=white)

## :notebook_with_decorative_cover:	 Notebook do meu projeto no Google Colab
<a target="_blank" href="https://colab.research.google.com/drive/15eG3-VMR0C5ha13MRfytce_Jg8-dhDrm?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
