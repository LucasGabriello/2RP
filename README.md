# 2RP Net - Engenharia de Dados

<br/>

## Decisões de arquitetura

### Ambiente de desenvolvimento e linguagens

<table>
  <tr>
  <th>Plataforma</th>
  <th>SQL</th>
  <th>Programação</th>
  </tr>
   <tr>
  <th><img src="https://cdn.freelogovectors.net/wp-content/uploads/2020/11/databricks-logo.png" width="100px;"> </th>
  <th><img src="https://d117h1jjiq768j.cloudfront.net/images/default-source/products/datadirect/dci-logos/spark-sql-logo.png?sfvrsn=97380b7f_2" width="100px;"></th>
  <th><img src="https://www.nobleprog.com.br/sites/hitrahr/files/category_images/height100_scale/pyspark_training.png?t=59415bb3" width="100px;"></th>
  </tr>
  </table>
  

 
### O Databricks foi escolhido devido ao suporte de diversas linguagens e serviços em nuvem, tendo também a possibilidade de ler dados de diversas fontes.
### 



## 💻 Pré-requisitos

Antes de começar, verifique se você seguiu aos seguintes requisitos:
* Fazer cadastro na plataforma <a href="https://databricks.com/try-databricks?itm_data=NavBar-TryDatabricks-Trial">`Databricks`</a>.
* Baixar e extrair arquivos .csv compactatos em <a href="">`heuheufhuhef.zip`</a>.


## 🚀 Instalando 

### Instalando noteook

Na tela inicial clique no icone do Workspace

Na aba Workspace clique no drop down e selecione a opção Import

Ao aparecer a tela de import selecione os arquivos anteriormente extraidos e prossiga na importação


### Subindo dados

Ao carregar o notebook clique no drop down responsavel pela função Upload Data

Faça o upload do arquivo 


### Executando!

Inicie a execução de todas as celulas e pronto!



## ☕ Organização do desenvolvimento...

#### A estrutura que foi criada segue o seguinte padrão.

* Criação do banco de dados
* Criação dos Dataframes a partir dos cvs

<hr/>

* Cração de tabela e tabela auxiliar

* Populando tabela auxiliar com respectivo Dataframe

* Populando tabela com tabela auxiliar com dados tratados

<hr/>

* Querys...

> Obs: O relacionamento entre tabelas é feito apenas de forma conceitual, pois não é possivel definir chaves primarias eestrangeiras no Spark SQL
<br/>

![image](https://user-images.githubusercontent.com/22823453/154786708-b7a22c9e-368e-42fd-be88-97c6d889751f.png)


## 📝 Tratamentos dos dados

* Tipagem das colunas
* Adicionar valor "NULL" para o padrão null do Spark
* trocar "," por "."

[⬆ Voltar ao topo](#nome-do-projeto)<br>
