# Reference : https://github.com/OWASP/NodeGoat


Instructions
# mkdir InHere && cd InHere

# git clone https://github.com/OWASP/NodeGoat.git

# apt install npm

# npm install

# npm auto fix        (npm audit)-> to check vulns?

 install mongodb
# apt -y install gnupg2

add to apt
# wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | sudo apt-key add -

add to the sources for updating
# echo "deb http://repo.mongodb.org/apt/debian buster/mongodb-org/4.2 main" | sudo tee /etc/apt/sources.list.d/mongodb-org.list

# apt update
# apt-get upgrade
# apt -y install mongodb-org

# mkdir /data/
# mkdir /data/db

Move into the NodeGoat dir
# cd <NodeGoat>/config/env/
# vim development.js
- uncomment the line thats says uncomment // db: 'mongodb://localhost:27017/nodegoat'

# npm install -g grunt
# grunt db-reset:development 

Run the mongo daemon -- run the mongo database which will be on port:27017
# mongod






launch the nodeGoat Application
# npm start
http://localhost:4000/
