Members
Don Aspecto
Jordan Chong
Joshua Corpuz
Johann Uytanlet

Dependencies
java jdk 17
node version 20.3.0
Apache Maven 3.9.9
mongod db version v6.0.7
mongosh 1.10.1

how to run application
have 7 cmd


create a data folder in the root folder and create a auth-service, course-service, and grade-service folder
create three separate mongodb databases
mongod --dbpath="C:\data\auth-service" --port 27017 --bind_ip 127.0.0.1
mongod --dbpath="C:\data\course-service" --port 27018 --bind_ip 127.0.0.1
mongod --dbpath="C:\data\grade-service" --port 27019 --bind_ip 127.0.0.1

in the project folder
cd frontend <- run the react appplication
npm i
npm start

cd auth-service <- run the bootstrap java backend
mvn clean install
mvn spring-boot:run

cd course-service <- run the bootstrap java backend
mvn clean install
mvn spring-boot:run

cd grade-service <- run the bootstrap java backend
mvn clean install -DskipTests
mvn spring-boot:run