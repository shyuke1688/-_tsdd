build:
	docker build -t tangsengdaodaoserver .
push:
	docker tag tangsengdaodaoserver 113.125.159.8:8086/im/tangsengdaodaoserver:latest
	docker push 113.125.159.8:8086/im/wukongchatserver:latest
deploy:
	docker build -t tangsengdaodaoserver .
	docker tag tangsengdaodaoserver 113.125.159.8:8086/im/tangsengdaodaoserver:latest
	docker push 113.125.159.8:8086/im/tangsengdaodaoserver:latest
deploy-v1.5.5:
	docker build -t tangsengdaodaoserver .
	docker tag tangsengdaodaoserver 113.125.159.8:8086/im/tangsengdaodaoserver:v1.5.5
	docker push 113.125.159.8:8086/im/tangsengdaodaoserver:v1.5.5
run-dev:
	docker-compose build;docker-compose up -d
stop-dev:
	docker-compose stop
env-test:
	docker-compose -f ./testenv/docker-compose.yaml up -d 