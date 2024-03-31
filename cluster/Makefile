up:
	docker compose up --detach

down:
	docker compose down

nginx_restart:
	docker compose restart nginx

clean:
	docker compose down --rmi all --volumes

.PHONY: up down clean nginx_restart
