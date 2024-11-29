# hadoop_full_pack
Full pack with Hadoop, Hive, Superset, Hue and Spark inside.

Commands:
git clone https://github.com/HoangNV2001/Docker-Hadoop-Hive-Spark-JupyterLab-Hue-Superset --config core.autocrlf=input
cd ./Docker-Hadoop-Hive-Spark-JupyterLab-Hue-Superset/docker-files
docker-compose up --no-start
docker start database, superset_cache, superset_db, superset_init
docker-compose up -d

Resources:
namenode	localhost:9870	
datanode	localhost:9864	
hive	localhost:10002	
hue	localhost:8888	
zeppelin	localhost:8090	
spark master	localhost:8080	
superset	localhost:8008	username:admin - password:admin
