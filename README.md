Você está trabalhando em um projeto em que duas clínicas médicas, 
a Clínica Sanare e a Clínica Reviver, estão passando por um processo de fusão.

Você está inserido no time de Engenharia de Dados como responsável por disponibilizar 
as informações de ambas as clínicas de uma maneira segura, reprodutível e ágil. 
No entanto, esses dados estão contidos em dois arquivos de origens diferentes e podem ser potencialmente incompatíveis. 
Como solução, você optou por utilizar o WSL para acessar uma máquina Linux virtual onde deverá criar uma estrutura de pastas para o projeto. 
O projeto inclui a criação de um ambiente virtual Python, a realização do download dos dados e o salvamento das etapas de trabalho em um script 
que pode ser compartilhado com toda a equipe.

1 - Configurar o ambiente e baixar os dados
WSL Ubuntu instalado
Download dos arquivos data_raw:
dados_empresaA.json
dados_empresaB.csv

2 - Criar ambiente virtual
python3 -m venv .venv
source .venv/bin/activate

3 - Baixar Jupyter (com versionamento)
pip install notebook==7.0.3

