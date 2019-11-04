# ci-taco
## Practicing project for golang
1. Gin framework
2. Connecting redis with redigo
3. Using gorm as orm.
4. JWT as authorization.
5. Using Mechinery and RabbitMQ for async task
6. Docker
7. Using Vue as front-end

## Quick Start
1. build front-end project (Keplan)
`docker-compose -f dev-frontend.yml up`
2. build & run back-end project (Taco & Kuma)
`docker-compose -f dev-backend.yml up -d`
3. Run http://localhost:8080
