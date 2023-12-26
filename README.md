# README

## GROUP <FinalProject>

- Member 1: <Nguyen Thi Lan Anh>
- Member 2: <Ha Thi Hong Anh>
- Member 3: <Nguyen Hoang Anh>
- Member 4: <Tran Hoang Anh>

## Starting server

- Run on your terminal `docker-compose up`
- Open browser at http://localhost:3000/
- Continue your work on a new terminal tab. Leave this terminal tab open until you want to stop the server.

## Stop server

`CTRL + C`

### Accessing docker container
**Remember to run this before any of the command below**

`docker exec -it ins20065-proj_app_1 /bin/bash`

### Bundle install
Installing required libraries, you can run this command multiple time. If there is an error, let make sure this command has been executed successfully.

`bundle install`

### Migrate database

`rails db:migrate`

## Optional

### Rails console

`rails c`
