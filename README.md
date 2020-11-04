# Install

## Install

	composer require --dev aamant/magento2-docker

## Prepare file 

	cp docker-compose.yml.dist docker-compose.yml.dist
	
or if you use jwilder/nginx-proxy

    cp docker-compose.yml.proxy.dist docker-compose.yml.dist

## Run

	docker-compose up -d