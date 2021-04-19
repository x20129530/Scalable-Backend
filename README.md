# Scalable-Backend
**admin application**
Step 1: First add the database with following configuration
Port:33066
host:localhost
user:root
Password:root
database : admin
and test the connection 
Step 2: build the docker compose file with this command
**docker-compose up --build**
Step 3: open new terminal and type this command to get into docker container backend service:
**docker-compose exec backend -sh**
Step 4:  after deleting the migration file fire this command inside docker
**python manage.py make migration**
Step 5: make migration with this command
**python manage.py migrate**

**main application**
Step 1: First add the database with following configuration
Port:33067
host:localhost
user:root
Password:root
database : main
and test the connection 
Step 2: build the docker compose file with this command
**docker-compose up --build**
Step 3: open new terminal and type this command to get into docker container backend service:
**docker-compose exec backend -sh**
Step 4:  after deleting the migration file fire this command inside docker
**python manager.py make migration**
Step 5: make migration with this command
**python manager.py migrate**

goto frontend github link : https://github.com/x20129530/Scalabe-frontend

follow the process of running the frontend
