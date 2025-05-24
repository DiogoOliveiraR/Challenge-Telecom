Análise de Evasão de Clientes - Telecom X
Descrição
Este projeto tem como objetivo a análise de dados de evasão de clientes (churn) na empresa Telecom X. O foco é entender os fatores que contribuem para a decisão de cancelamento de serviços e gerar insights que ajudem a reduzir essa taxa de evasão.

Problema
A Telecom X enfrenta um alto índice de cancelamento de clientes, o que impacta diretamente a receita da empresa. A análise foi conduzida com o intuito de identificar padrões e comportamentos de clientes que podem estar associados à evasão.

Tecnologias e Bibliotecas Utilizadas
Python: Linguagem principal utilizada para análise e manipulação de dados.

Pandas: Biblioteca para manipulação e análise de dados.

Matplotlib/Seaborn: Bibliotecas para visualização de dados.

Jupyter Notebook: Ambiente interativo para desenvolvimento da análise.

Instalação e Dependências
Para rodar este projeto localmente, siga os passos abaixo:

1. Clone o repositório
bash
Copiar
Editar
git clone https://github.com/ingridcristh/challenge2-data-science.git
2. Instale as dependências
Certifique-se de ter o Python 3.x instalado. Crie um ambiente virtual e instale as dependências:

bash
Copiar
Editar
cd challenge2-data-science
python -m venv venv
source venv/bin/activate  # Para Linux/Mac
venv\Scripts\activate     # Para Windows
pip install -r requirements.txt
3. Execute o Jupyter Notebook
bash
Copiar
Editar
jupyter notebook
Abra o arquivo do notebook no navegador e execute as células para reproduzir a análise.

Estrutura do Projeto
TelecomX_Data.json: Arquivo JSON com os dados brutos da Telecom X.

Análise_Churn.ipynb: Jupyter Notebook com o código de análise de dados, visualizações e insights.

requirements.txt: Lista de dependências do Python necessárias para rodar o projeto.

Como Executar o Projeto
Importação de Dados: O código começa com a importação do arquivo JSON, que contém informações dos clientes.

Limpeza de Dados: São realizadas operações de tratamento de valores ausentes, correção de tipos de dados e criação de novas variáveis, como Contas_Diarias.

Análise Exploratória de Dados (EDA): São feitas análises descritivas e gerados gráficos para visualizar padrões no comportamento dos clientes.

Conclusões e Recomendações: Ao final, o notebook apresenta os insights encontrados e as sugestões para reduzir a evasão.

Possíveis Problemas e Soluções
Problema 1: Erro ao carregar os dados do arquivo JSON
Solução: Verifique se o arquivo TelecomX_Data.json está presente na pasta correta e se o caminho foi definido corretamente no código.

Problema 2: Dependência de bibliotecas não instalada
Solução: Certifique-se de rodar pip install -r requirements.txt para instalar todas as dependências do projeto.

Conclusão
Este projeto fornece uma base sólida para entender os fatores que influenciam a evasão de clientes na Telecom X, com insights e sugestões de ações estratégicas para mitigar esse problema. Ao executar as etapas de análise e visualização de dados, o objetivo é fornecer à equipe de marketing e operações as ferramentas necessárias para reduzir o churn e melhorar a retenção de clientes.
