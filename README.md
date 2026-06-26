# RedesComplexas

1. Clonar o Repositório e Acessar a Pasta
No seu terminal, execute o comando abaixo para clonar o projeto e navegar até o diretório:

Bash
git clone https://github.com/VanessaMSilva/Trabalho---Redes-Complaxas.git
cd Trabalho---Redes-Complaxas
2. Instalar as Dependências (Recomendado)
Para garantir que você tenha todas as bibliotecas necessárias (como networkx, pandas, matplotlib, etc.), você pode instalar via pip:

Bash
pip install -r requirements.txt
(Caso não tenha um arquivo requirements.txt criado, você pode instalar as principais rodando: pip install pandas networkx matplotlib matplotlib-inline notebook)

3. Execução do Ambiente
Escolha uma das opções abaixo para rodar o notebook:

Opção A: Via Jupyter Notebook (Local)
Inicie o Jupyter localmente com o comando:

Bash
jupyter notebook
Após o navegador abrir, localize e execute o arquivo principal do projeto: TrabalhoRedes.ipynb (ou o arquivo correspondente). No menu superior, clique em Cell > Run All.

Opção B: Via Google Colab (Nuvem)
Faça o download do repositório como ZIP (ou use a pasta clonada).

Faça o upload da pasta para o seu Google Drive.

Abra o arquivo TrabalhoRedesComplexas.ipynb no ambiente do Colab.

Caso necessário, monte o seu Drive na primeira célula do notebook para ler os conjuntos de dados:

Python
from google.colab import drive
drive.mount('/content/drive')
No menu superior do Colab, clique em Ambiente de Execução > Executar tudo (ou use o atalho Ctrl + F9).
