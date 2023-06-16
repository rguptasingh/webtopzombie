# webtopzombie
This projects illustrates that https doesn't always mean the site is super-secure.

It will show you how to host beef via a server to make it accessible to the public so you can actually use the hook-link of it. Of course you should only do that if all parties or people involved have agreed to do that. Please don't do anything illegal. Hosting beef will be done with ngrok. I will also guide you through on how to configure ngrok in order to host beef with a https-url.

Another thing this project will cover is how to setup a webtop in order to avoid being affected by a hooked-browser. A webtop is simply a linux-environment running within a container that you can access through the web-browser. After you have completed your surfing session you can simply take down the container with the command `docker-compose down -v`. The `-v` option is there to make sure all associated storages are wiped too so you can really start with a fresh-browser after each session.
