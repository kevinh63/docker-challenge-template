# Challenge1
-cd into challenge1
-use "docker build -t webserver ." in terminal
-use "docker run -d -p 8080:80 webserver"
-go to "http://localhost:8080/"

# Challenge2
-cd into challenge2
-use "docker-compose up --build" in terminal
-go to "http://localhost:3000/api/books" 
-go to "http://localhost:8080/api/books/1"

# Challenge3

-create two new files, .env and docker-compose.yml
-populate the files with the needed code
-cd into challenge3
-put "docker-compose up --build" in terminal
-go to "http://localhost:8080/api/books"

# Challenge4

-exact same as challenge3
-cd to challenge4
-this time put "docker-compose up --build --scale node-service=3" in the terminal
-go to cmd
-cd into challenge4 folder
-run "docker-compose ps"


