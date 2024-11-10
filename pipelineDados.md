# O que é pipeline de dados ?

O que passa no pipeline são os dados, basicamente pegar de um lugar para outro, origem até o destino , como um data warehouse, ou data lake. Ao longo do caminho os dados são transformados, para serem usados para gerarem insights de negócios.

Os dados da origem são brutos, é preciso limpar os dados para entregar insights aos tomadores de decisão. 

Pipelines de dados modernos automatizam muitas das etapas manuais envolvidas na tranformação e otimização do carregamento de dados. O pipeline inclui carregar dados para uma tabela de preparação(Staging Area) para armazenamento temporário e, em seguida, alterá-los antes de inserí-lo no destino.

O Data lake é o  centro de armazenamento de dados brutos.

## Componentes de um Pipiline de dados.

1.  Origem

Muito importânte. Banco de dados transacional, por exemplo, cria o pipeline, começa a extrair os dados e pode dar problema, pois sobrecarrega a origem, dando problemas para usuários.

2.  Processamento, limpeza, tranformação dos dados. Para facilitar o processo de análise. Etapa mais complexa e extensa. 

3.  Destino. Onde colocará os dados ? Datawarehouse, Datalake, nuvem. 

## Pipeline de dados x Pipeline ETL. 

ETL , movem os dados, carregam os dados para um destino . Porém ´apenas um subprocesso de pipeline de dados. 

Todo pipeline ETL é um pipeline de dados, mas nem todo pipeline de dados é um pipeline ETL. 

Um pipeline de dados é mais amplo, pois é todo o processo envolvido no transporte de dadps de um local para outro, incluindo limpeza, tranformação, enriquecimento, segurança, orquestração integração/entrega contínua.

Um pipeline de dados pode ser composto por vários pipelines ETL. 

### Principais características ao considerar um pipeline dedados.

*   Processamento de dados contínuo e extensível
*   Agilidade e elasticidade danuvem
*   Recursos isolados e independêntes para processamento de dados.

*   Acesso democratizado a dados e gerenciamento de autoatendimento.

*   Alta disponibilidade e recuperação de desastres.

## Principais ferramentas 

*   AWS Glue 
*   Apache Airflow -> Baseado em liguagem python. 
*   dbt
*   Apache Kafka -> trabalhar com dados em tempo real. 
*   Apache Spark -> Pode fazer ETL com o apche spark. 
*    Apache BEAM -> Requer conhecimentos em programção
*    Airbyte -> Não requer conhecimentos em programação.
*   Stitch
*   Keboola
*   dremio
*   fivetran
*   dataform



* Empresas tradicional

Usam ferramentas mais antigas , levam um pouco mais de tempo para aderir novas tecnologias. 

*   Start Ups.

## Armazenamento e cloud

*   Azure Data Factory
*   Databricks, basicamente é o apache spark em um ambiente em nuvem. Estão investindo no conceito de datalakehouse
*   Delta lake
*   Apache Hadoop

##  Real time analytics

*   Tableau -> Conecta direto ao pipeline e a mdedida que os dados vão tranformando, é possível ver isso em tempo real. Não é preciso armazenar e depois criar gráficos

*   Amazon Kinesis ->   
*   Azure Synapse Analytics
*   Dataedo
*   Power BI

Metadado : Dado sobre dado 
