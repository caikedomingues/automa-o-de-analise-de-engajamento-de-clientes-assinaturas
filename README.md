# Automação de Análise de Engajamento de clientes (assinaturas)
Automação de Analise de dados realizada com python e powerbi que tem como objetivo realizar um modelo preditivo que indica a probabilidade de um usuário cancelar a assinatura de uma empresa ficticia que oferece
planos de gerenciamento de projetos.

# Ferramentas Utilizadas:
python 3.12.10: Irá realizar a automação que ira coletar, tratar e analisar os dados com o objetivo de criar modelos de predição que
classificarão os clientes com maior probabilidade de cancelar a assinatura.

powerbi: Ira criar o dashboard que ira traduzir os resultados encontrados na predição do modelo.

# Pastas do sistema
-> Treinamento: Ira conter o arquivo csv que será utilizado no
treinamento do modelo. 

-> Dados: Ira conter os arquivos que serão utilizados na predição

-> Logs: Ira conter os arquivos de logs que contém as etapas de 
cada execução do projeto

-> Relatórios: Ira conter os arquivos que serão utilizados na
construção do dashboard.

-> Historico: Ira conter todos os arquivos que ja foram utilizados
no sistema

# Informações da fonte de dados utilizada

link da fonte de dados na kaggle: https://www.kaggle.com/datasets/suhanigupta04/saas-customer-churn-prediction-dataset

contexto: Base de dados de uma empresa ficticia de que fornece assinaturas de gerenciamento de projetos. O autor da base de
dados utilizou dados sinteticos usando a biblioteca Faker do Python, onde ele gerou tanto o arquivo de teste quanto o 
de treino.

Colunas:
ID_do_Cliente: Identificador único para cada cliente

Nome: Nome Completo do cliente

Email: Endereço de e-mail do cliente

Idade_da_conta: Idade da conta em dias

Frequencia_login: Com que frequência o cliente realiza login na plataforma.

Minutos_uso_diario: Média de Minutos gastos usando o software por dia

Ultimo_ticket_de_suporte: Conteudo textual de suporte mais recente

rotatividade: Indica se o cliente cancelou ou não a assinatura (coluna
que o modelo irá prever o valor).

# Bibliotecas e funções Utilizadas:

-> os: Ira acessar as pastas que contém os arquivos utilizados no
sistema

-> pandas: Irá acessar, analisar e tratar os dados que serão usados
no treino e na predição do modelo.

-> LogisticRegression: Como estamos lidando com uma predição de classificação, vamos utilizar a regressão logistica como modelo.

-> LabelEncoder: Classe que codifica dados categóricos que possuem uma ordem lógica

-> OneHotEncoder: Classe que codifica dados categóricos que não possuem uma ordem lógica.

-> datetime: Módulo que ira registrar a data e hora em que cada etapa do processo foi executada.

# O que o Python faz:
-> Ira criar todas as pastas necessárias para o desenvolvimento
do projeto. (Deve ser criada em um arquivo separado, pois, dessa 
forma evitamos quebrar a execução da automação por conta da falta
de arquivos na pasta)

-> Irá acessar a pasta que contém o arquivo que será utilizado
no modelo de predição.

-> Ira verificar a extensão do arquivo antes de realizar a predição

-> Ira tratar e preparar os dados que serão usados no treinamento 
do modelo.

-> Ira acessar a pasta que contém os arquivos que serão utilizados
no modelo de predição para a geração do relatório.

-> Ira conter logs indicam cada etapa do processo registrando a
data e a hora da execução de cada etapa. Cada dia terá o seu arquivo
log com as execuções da automação.

-> Ira gerar um relatório com os dados trataados e classificados para
serem utilizados na construção do dashboard.

-> Ira transferir os arquivos para uma pasta que conterá todos os arquivos
que ja foram tratados e analisados.

# Classificações do modelo:
-> Baixo: Possui baixa ou nenhuma probabilidade de cancelar a assinatura.

-> Médio: Ira representar clientes que podem ou não cancelar a assinatura,
ou seja, clientes "indecisos" e imprevisiveis que podem ir de um pico a
outro a qualquer momento.

-> Alto: Possui alta probabilidade de cancelar a assinatura

# O que o PowerBI faz:
-> Calcula a taxa de Cancelamento

-> Total de Contas em Risco.

-> lista de contas prioritárias para a ação de retenção. 

