# Day 6 Commands - Docker Networking Basics

> Date: 24-03-2026


## Commands performed
1. docker network ls
2. docker network inspect bridge
3. docker run -d -p 8081:80 nginx
4. docker ps


## Extra practice commands
5. docker network create mynet
6. docker run -d --name web1 --network mynet nginx
7. docker exec -it web1 sh
8. docker network connect mynet <container-name>
9. docker network rm mynet
