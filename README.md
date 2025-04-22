## Desafio Azure Databricks – DIO

Este projeto faz parte do desafio prático da DIO, com o objetivo de testar e reforçar meus conhecimentos sobre os conceitos e recursos da plataforma **Azure Databricks**.

## 📌 Objetivo

Associar corretamente os principais conceitos e funcionalidades do Azure Databricks às suas descrições por meio de lógica de programação simples em Python.

## 🧠 Conceitos trabalhados

- **DBFS** → Sistema de Arquivos do Databricks  
- **Lakehouse** → Integra Data Lake e Data Warehouse  
- **Delta Lake** → Camada de armazenamento de dados open-source  
- **Workspace** → Ambiente colaborativo para dados e código  

## ⚙️ Funcionalidades exploradas

- **IA** → Criação e implantação de IA generativa em escala  
- **Armazenamento** → Armazenamento otimizado com arquitetura lakehouse  
- **ETL** → Processamento de dados em lote e em tempo real  
- **Governança** → Controle e segurança unificada de dados e IA  
- **Compartilhamento de dados** → Compartilhamento rápido de dados, modelos e notebooks  

## 💡 Insights

Durante a construção deste desafio, compreendi melhor como o **Databricks** funciona como um ambiente poderoso para ciência de dados e inteligência artificial, com foco em performance, escalabilidade e colaboração.

## 📸 Prints do Projeto

### ➤ Execução do conceito:

# Recebe a entrada do usuário

    entrada = input()

# Função responsável por receber um conceito e retornar sua respectiva descrição

    def descrever_conceito(conceito):

    if conceito == "DBFS":
    
        return "Sistema de Arquivos do Databricks"
        
    elif conceito == "Lakehouse":
    
        return "Integra Data Lake e Data Warehouse"
        
    elif conceito == "Delta Lake":
    
        return "Camada de armazenamento de dados open-source"
        
    elif conceito == "Workspace":
    
        return "Ambiente colaborativo para dados e código"
        
    else:
    
        return "Conceito não reconhecido"

# Imprime a descrição do conceito recebido

    print(descrever_conceito(entrada))


## 📸 Prints do Projeto

### ➤ Execução do recurso:

# Recebe a entrada do usuário
    
    entrada = input()

# Função responsável por receber um recurso e retornar sua respectiva descrição

    def descrever_recurso(recurso):

    if recurso == "IA":
    
        return "Criação e implantação de IA generativa em escala"
        
    elif recurso == "Armazenamento":
    
        return "Armazenamento otimizado com arquitetura lakehouse"
        
    elif recurso == "ETL":
    
        return "Processamento de dados em lote e em tempo real"
        
    elif recurso == "Governança":
    
        return "Controle e segurança unificada de dados e IA"
        
    elif recurso == "Compartilhamento de dados":
    
        return "Compartilhamento rápido de dados, modelos e notebooks"
        
    else:

        return "Recurso não reconhecido"

# Imprime a descrição do recurso recebido

    print(descrever_recurso(entrada))


📊 Desafio – Opções de Preço do Azure Databricks

## 📸 Prints do Projeto

## Recebe a entrada do usuário e armazena na variável "entrada"

    entrada = input("Digite uma opção de preço do Azure Databricks: ")

## Função responsável por receber uma opção de preço e retornar sua respectiva descrição


    def descrever_precificacao(opcao):

    if opcao == "Pago conforme o uso":
      
        return "Pague por segundo, sem compromissos. Escalável sob demanda"
   
    elif opcao == "Plano de economia do Azure":
        
        return "Compromisso de gasto fixo por hora (1 ou 3 anos) com preços reduzidos"
  
    elif opcao == "Instâncias Reservadas":
       
        return "Desconto por compromisso com instâncias por 1 ou 3 anos"
   
    elif opcao == "Instâncias Spot":
       
        return "Capacidade ociosa com grandes descontos, mas sujeita à interrupção"
    
    else:
        
        return "Opção de preço não reconhecida"

## Imprime a descrição da opção de precificação recebida

    print(descrever_precificacao(entrada))

##🔧 Desafio – Recursos Azure Relacionados ao Databricks

## Recebe a entrada do usuário e armazena na variável "entrada"

    entrada = input("Digite o nome do recurso Azure: ")

## Função responsável por receber um recurso e retornar sua respectiva descrição

    def descrever_recurso(recurso):

    if recurso == "Azure Data Factory":
        
        return "Serviço de integração de dados híbridos e orquestração para ETL e ELT"
        
    elif recurso == "Azure Databricks":
       
        return "Plataforma Azure de análise de dados baseada em Apache Spark"
        
    elif recurso == "Microsoft Fabric":
        
        return "Plataforma unificada de análise de dados da Microsoft"
    
    elif recurso == "Azure Synapse Analytics":
    
        return "Serviço de análise que combina big data e data warehousing"
    
    else:
    
        return "Recurso não reconhecido"

## Imprime a descrição do recurso recebido

    print(descrever_recurso(entrada))

## Importar arquivo CSV para o databricks

    import pandas as pd

# URL do arquivo CSV

    url = "https://raw.githubusercontent.com/MicrosoftLearning/mslearn-databricks/main/data/products.csv"

# Lê o CSV diretamente da URL

    df = pd.read_csv(url)

# Exibe o DataFrame

    print(df)

# Filtrar Road Bikes

    df_filtered = df[df['Category'] == 'Road Bikes']
    display(df_filtered)
