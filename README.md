# 2RP Net - Engenharia de Dados

<br/>

## 🗄 Ambiente de desenvolvimento e linguagens

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
  

 
> O Databricks foi escolhido devido ao suporte de diversas linguagens e serviços em nuvem, tendo também a possibilidade de ler dados de diversas fontes.
>  Assim como as ferramentas Spark que atendem a diversos volumes de dados.

<br/>


## 💻 Pré-requisitos

>Antes de começar, verifique se você seguiu aos seguintes requisitos:
* Fazer cadastro na plataforma <a href="https://databricks.com/try-databricks?itm_data=NavBar-TryDatabricks-Trial">`Databricks`</a>
* Ter baixado o notebook <a href="https://github.com/LucasGabriello/2RP/raw/main/2RP.dbc">`2RP.dbc`</a>
* Ter baixado e extraido arquivos .csv compactatos em <a href="https://github.com/LucasGabriello/2RP/raw/main/dados.zip">`dados.zip`</a>
### ou
```
gh repo clone LucasGabriello/2RP
```


## 🚀 Instalando 

### Instalando notebook

>Ja na tela inicial do Databricks clique no icone do Workspace

![img1](https://user-images.githubusercontent.com/22823453/154808436-ea41067d-05ee-42dc-a768-87f8d9133c0d.png)
<br/>

>Na aba Workspace clique no drop down e selecione a opção Import

![img2](https://user-images.githubusercontent.com/22823453/154808478-defb2b08-45dc-4ad4-a729-1d35fb59052c.png)
<br/>

>Ao aparecer a tela de import selecione o notebook anteriormente baixado e prossiga na importação

![img3](https://user-images.githubusercontent.com/22823453/154808496-23055679-8bf7-4c2a-a791-6c84d4a22922.png)
<br/>

### Subindo dados

>Ao carregar o notebook clique no drop down responsavel pela função Upload Data, selecione os arquivos anteriormente extraidos e prossiga na importação

![img4](https://user-images.githubusercontent.com/22823453/154808559-9178f322-8a68-4cc8-ab6a-b048e15995fa.png)
<br/>

>Faça o upload dos arquivos 

![img5](https://user-images.githubusercontent.com/22823453/154808563-0740acb0-cc86-49b5-95f1-f0d2f162fbd8.png)
<br/>

### ▶ Executando!

>Inicie a execução de todas as celulas e pronto!

![img6](https://user-images.githubusercontent.com/22823453/154808570-dc8a9ac9-3b3f-44bf-89db-bb5ec9624b92.png)
<br/>

>Obs: O cluster necessário para rodar a aplicação será criado automaticamente caso você não tenha selecionado algum já existente previamente (opcional para fins didáticos).

<br/>

## ☕ Organização do desenvolvimento...

### A estrutura que foi criada segue o seguinte padrão.

<hr/>

* Criação do banco de dados

* Criação dos Dataframes a partir dos cvs

<hr/>

* Cração de tabela e tabela auxiliar

* Populando tabela auxiliar com respectivo Dataframe

* Populando tabela com tabela auxiliar com dados tratados

<hr/>

* Querys...
<hr/>

> Obs: O relacionamento entre tabelas é feito apenas de forma conceitual, pois não é possivel definir chaves primarias eestrangeiras no Spark SQL
<br/>

![image](https://user-images.githubusercontent.com/22823453/154786708-b7a22c9e-368e-42fd-be88-97c6d889751f.png)

<br/>

## 📝 Tratamentos dos dados

>Segue os principais dados que foram tratados

* Tipagem das colunas
* Adicionar valor "NULL" para o padrão null do Spark
* trocar "," por "."

[⬆ Voltar ao topo](#nome-do-projeto)<br>
