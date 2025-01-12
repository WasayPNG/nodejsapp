# nodejsapp
Basic NodeJS application with a Dockerfile

On a machine that has Docker Engine installed, use these commands inside the project directory:

``docker build .``

After you create the image, create a container and export local port 3000 to port 80 from the container using ``-p`` flag:

``docker run -p 3000:80 <docker image>``

You can find the docker image name using command ``docker images``

After you use the ``docker run`` command you can open ``localhost:3000`` in any browser in local machine
