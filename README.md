# Full pack for Hadoop developers
## Requirements
You need to have Docker and Docker-Compose installed.

## Set up
### Installation guide

	
	git clone https://github.com/knight99rus/hadoop_full_pack --config core.autocrlf=input

 	cd ./hadoop_full_pack/docker-files

	docker-compose up --no-start

	docker start database, superset_cache, superset_db, superset_init

	docker-compose up -d

**Note:** 
* **Use** `--config core.autocrlf=input` **on cloning to handle Unix line endings**
* **Start** `database`, `superset_cache`, `superset_db`, `superset_init` **first.**
## List of services 
**Only list services with GUI, see docker-compose.yml file for details about all services and their versions.**

Service|URL (only list GUIs)|Notes|
| :---:   | :---: | :---: |
namenode|localhost:9870||
datanode|localhost:9864||
hive|localhost:10002||
hue|localhost:8888||
spark master|localhost:8080||
superset|localhost:8008|username:admin - password:admin|




