# Setting up beef
## Install beef (arch)
In order to install beef simply type `yay -S beef-git`. After that beef will be located at /usr/share/beef by default. Navigate to that path with `cd /usr/share/beef`. There you will have to edit the config.yaml file in order to make this whole project work. In that file please be sure to change:
+ The default login-credentials
+ Uncomment the public section to run the beef in an actual url. 
+ Replase the host ip in the public section with the ngrok id.
+ Set the public port to 443.
+ Set allow_reverse_proxy to true.
+ change the localhost port beef listens on to avoid port-conflicts with our webtop.
After you have done this you can run beef with the command `sudo ./beef`.
