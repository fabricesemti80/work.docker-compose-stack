#& default rules
.PHONY: default
default: restart

.PHONY: restart
restart:
	docker-compose down && docker-compose up -d

.PHONY: up
up:
	docker-compose up -d && docker ps

.PHONY: down
down:
	docker-compose down