

# install postgres and pgadmin (Db related)
# install nodejs 
create Datbase name api 
# some querys
CREATE TABLE users (
  ID SERIAL PRIMARY KEY,
  name VARCHAR(30),
  email VARCHAR(30)
);
INSERT INTO users (name, email)
  VALUES ('Jerry', 'jerry@example.com'), ('George', 'george@example.com');

# to install express pg 
npm i express pg

# to run
node index.js

some urls
 # http://localhost:3000/users 
 # http://localhost:3000/users/1,