# DERoadMap01
Roadmap for Data Engineering 01

soluciones tecnologicas que utilizamos para desarrollo.

- sql, python, javascript, java, rpg, genexus, linux y docker commands.

- dbeaver, vscode, pentaho, knime, h2o.ai, fastapi, flask, elk, diagrams.net, cognos, tm1/planning, openshift, jenkins

- db2i, sqlserver, tm1, elasticsearch, cassandra y clickhouse(etapa pruebas e implementaciones)




Roadmap for Data Engineering

1. Computer Science Fundamentals Overview:
Revision general de los fundamentos sobre CS Computer Science  (Ciencia Computacional)


2. Building Foundation (foundation skills): 

- habilidades importantes(lenguajes para gestionar data): python y sql


3. Core Data Engineering Foundation

- DataWare vs DataLake vs LakeHouse

Learning about core Data Warehouse fundamentals (that don’t change): 
It includes learning about OLAP vs OLTP, Dimension Table, Extract Transform Load, 
ER Modeling, or Dimension Modelling such as understanding fact and dimension tables


4. Data Architecture Knowledge (Plataforma de Datos)

4.1 Data Storage (principalmente basados en Object Storage/ FileSystem)

- Basados en S3: Minio, AWS S3, etc


4.2 Data Format(Storage Format)

- Open Table Formats, CSV, JSON, AVRO, or Parquet file formats.
- Delta Lake(DataBricks), Apache Iceberg(el de facto standard open source rest protocol), Apache Hudi
- OneTable(Apache XTable) targets 'interoperability' among different lakehouse table formats


4.3 Data Processing Engine (Compute Engines)

- batch processing: pyspark
- real time processing: kafka/confluent


4.4 Data Pipeline(Workflow Orchestration)

- airflow
- knime 
- pentaho



4.5 Data Catalog (catalogos pensados para trabajar con diferentes clouds, formatos de datos y plataforma de datos)

- Spark Catalog (integrado con Apache Spark)
- Polaris (apache license....snowflake)
- Unity Catalog (apahce license....databricks)


4.6 Metastore

- Apache Hive (Hive MetaStore) + un Metastore DB (PostgreSQL)



4.7 SQL Gateway

- Apache Kyuubi


Datos Adicionales:
* DataBricks fue fundado por los creadores de Apache Spark, DataBricks es el pionero de una arquitectura de lakehouse, DataBricks tambien integra funcionalidades de AutoML(h2o.ai, pycaret, etc) y MLFlow
* Apache Spark reemplaza a Map Reduce
* Los que apuestan por Delta Lake ofrecen transacciones ACID para sus data lakes.

  

5. Kubernets/OKD/OpenShift/qovery

6. Proveedor Nube: AWS/GCP/AZURE, etc

