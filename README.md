# You need add in your /etc/host


127.0.0.1 app1.itshellweb.org 

127.0.0.1 app2.itshellweb.org

# Later, running: 

docker-compose up --build

# Check works urls:
prometheus: http://localhost:9090/

traefik: http://localhost:8085/     #user: admin 
                                    #pass: testing
                                    
app1: http://app1.itshellweb.org

app2: http://app2.itshellweb.org

#

# Grafana read prometheus data and dashboard with status codes , response time ,etc.

Grafana: http://localhost:3000 #Login with admin #user: admin #pass: test

# For test metrics

traefik: http://localhost:8085/metrics

or

View metrics in prometheus using dashboard and querys.

# Stop Stack:

docker-compose down

