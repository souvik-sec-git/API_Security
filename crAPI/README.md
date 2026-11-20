### crAPI for Linux installation:

1. curl -L -o /tmp/crapi.zip https://github.com/OWASP/crAPI/archive/refs/heads/main.zip  

2. unzip /tmp/crapi.zip  

3. cd crAPI-main/deploy/docker  

4. sudo apt update  

5. sudo apt install docker.io -y  

6. docker compose pull  

7. docker compose -f docker-compose.yml --compatibility up -d  

#### visit:  

http://localhost:8888 (Website)  

http://localhost:8025 (mails)
