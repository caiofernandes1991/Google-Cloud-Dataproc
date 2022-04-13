# Criando um Ecossistema Hadoop Totalmente Gerenciado com Google Cloud Dataproc

<p align="center"><img src="https://hermes.digitalinnovation.one/certificates/cover/76C5EF46.jpg" ></p>

## GCP Dataproc

Sua missão será criar um ecossistema de Big Data usando o Google Cloud Platform (GCP). Para isso, o expert te ensinará a configurar o Google Cloud Dataproc, um Hadoop totalmente gerenciado, usando seus créditos gratuitos da GCP.

### Criando um ecossistema Hadoop totalmente gerenciado com Google Cloud Platform

O desafio consiste em efetuar um processamento de dados utilizando o produto Dataproc do GCP. Esse processamento irá efetuar a contagem das palavras de um livro e informar quantas vezes cada palavra aparece no mesmo.

### Etapas do Desafio

1. Criar um bucket no Cloud Storage
1. Atualizar o arquivo ```contador.py``` com o nome do Bucket criado nas linhas que contém ```{SEU_BUCKET}```.
1. Fazer o upload dos arquivos ```contador.py``` e ```livro.txt``` para o bucket criado (instruções abaixo)
    - https://cloud.google.com/storage/docs/uploading-objects

1. Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando ```gs://{SEU_BUCKET}/contador.py```
1. O Job irá gerar uma pasta no bucket chamada ```resultado```. Dentro dessa pasta o arquivo ```part-00000``` irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.

### Entrega do Resultado

1. Criar um repositório no GitHub.
2. Criar um arquivo chamado ```resultado.txt```. Dentro desse arquivo, colocar as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.
3. Inserir o arquivo ```resultado.txt``` no repositório.

---

## Link deste Desafio

<a href="https://web.dio.me/lab/criando-um-ecossistema-hadoop-totalmente-gerenciado-com-google-cloud-dataproc/learning/f1c459e1-34e3-4d08-b654-d6cffc08ac5b" target="_blank">Bootcamp Cognizant Cloud Data Engineer #2</a>
<br>


