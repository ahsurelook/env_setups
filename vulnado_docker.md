# Install Vulnado on kali linux (2020.1) in Docker, February 2020

> curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -

> echo 'deb [arch=amd64] https://download.docker.com/linux/debian buster stable' | sudo tee /etc/apt/sources.list.d/docker.list

> apt-get install docker-ce

> apt-get update

> docker-compose build

> docker run hello-world

> apt-get install docker-compose 

**download vulnado**
> git clone git://github.com/ScaleSec/vulnado

**Move into vulnado**
> cd vulnado

**Launch the Vulnado Application**
> docker-compose up

**Open the application in a browser**
> localhost:1337





