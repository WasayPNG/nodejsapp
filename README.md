# nodejsapp
Basic NodeJS application with a Dockerfile and docker-compose.yml files

On a machine that has Docker Engine installed, use these commands inside the project directory:

``docker build -t nodejs-basic-app .``

You can find the docker image name using command ``docker images`` with tag ``nodejs-basic-app``

After you create the image use command ``docker compose up -d`` to start the container detached from that terminal.

After you use the ``docker compose`` command you can open ``localhost:3000`` in any browser in local machine.

To stop the container, use ``docker compose down`` in the project directory. 
