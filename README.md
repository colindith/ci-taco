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
1. build the front-end project (Keplan)<br />
`docker-compose -f dev-frontend.yml up`
2. build & run the back-end project (Taco & Kuma)<br />
`docker-compose -f dev-backend.yml up -d`
3. Run http://localhost:8080<br />
