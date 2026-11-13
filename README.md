# Automação de Análise de Engajamento de clientes (assinaturas)
Automação de Analise de dados realizada com python e powerbi que tem como objetivo realiazar um modelo preditivo que indica a probabilidade de um usuário cancelar a assinatura.

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
do projeto.

-> Irá acessar a pasta que contém o arquivo que será utilizado
no modelo de predição.

-> Ira tratar e preparar os dados que serão usados no treinamento 
do modelo.

-> Ira acessar a pasta que contém os arquivos que serão utilizados
no modelo de predição para a geração do relatório.

-> Ira verificar a extensão do arquivo antes de realizar a predição

-> Ira conter logs indicam cada etapa do processo registrando a
data e a hora da execução de cada etapa

-> Ira gerar um relatório com os dados trataados e classificados para
serem utilizados na construção do dashboard.

-> Ira transferir os arquivos para uma pasta que conterá todos os arquivos
que ja foram tratados e analisados.

# O que o PowerBI faz:
-> Calcula a taxa de Cancelamento

-> receita recorrente mensal em risco (MRR at Risk)

-> lista de contas prioritárias para a ação de retenção. 

