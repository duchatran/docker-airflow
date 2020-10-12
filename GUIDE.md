
#  Run Options:
+ Single Container: 
	docker run -
+ LocalExecutor:
	docker-compose -f docker-compose-LocalExecutor.yml up -d
+ CeleryExecutor:
First put in the path to the DAG folder to env-prod.txt, then run:
	docker-compose -f docker-compose-LocalExecutor.yml --env-file env-prod.txt up -d

