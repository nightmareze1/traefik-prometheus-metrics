# You need add in your /etc/host

127.0.0.1 app1.itshellweb.org 

127.0.0.1 app2.itshellweb.org

# Later, running: 

docker-compose up --build

# Check works urls:
prometheus: http://localhost:9090/

traefik: http://localhost:8085/

app1: http://app1.itshellweb.org

app2: http://app2.itshellweb.org

# Stop Stack:

docker-compose down

