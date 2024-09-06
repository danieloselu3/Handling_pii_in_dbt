.PHONY: up down dbt-run add-dbt-tbls dbt-compile

up:
	docker-compose --project-name hpiv up -d 

down:
	docker-compose down

add-dbt-tbls:
	docker-compose --project-name hpiv run dbt build
 
dbt-compile:
	docker-compose --project-name hpiv run dbt compile

dbt-run:
	docker-compose --project-name hpiv run dbt run