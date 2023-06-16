# The configuration steps to setup a webtop.
## Creating the docker-compose file and pulling the image
I have created a docker-compose.yaml file that you can immediately use. However, I would recommend you to make minor changes to some parameters such as the timezone or and the password. You can download my file from this repository under the path "webtopzombie/tutorials/webtop".

After you have created the file make sure to have Docker installed on your system. If not, please refer to the Docker Documentation. In order to run the container you will have execute the command `docker-compose up` and optionally add the `-d` option. After you have done this you can access your webtop at localhost:3000. It may take some time for the webtop to start.
