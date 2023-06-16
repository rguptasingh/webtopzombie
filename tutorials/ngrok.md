# Setting up ngrok
## Create an account
Before you follow my tutorial please be sure to create a ngrok account and link the token with your linux system. 
## Creating a tunnel and making your application accessible
Make sure you have installed ngrok via the command-line. In order to create a tunnel and make your application that will be beef in our case accessible to the pulbic you have to execute the command `ngrok http <port>`. Replace the portnumber with the portnumber beef will be running on. It should explicitly not be 3000 since our webtop already uses that port. The beef.md under the path webtopzombie/tutorials/ contains the necessary measures to change the portnumer for beef.
