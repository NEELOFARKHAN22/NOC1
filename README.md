
# POC1:-
```sh
- Deploy an Ubuntu server.
- Create a React app 
- Deploy react app on Apache Server
- Attach a domain -freely
- Attach Https SSL to the website
```
# Solutions:
```sh
Install the npm command using- `_sudo apt install npm_`

Install a react app - `sudo npm install -g create-react-app`

Create a react app - `sudo create-react-app test1`

Navigate the test1 app via the `cd` command.

Run the app - `npm run build`

#I got the error and resolved it by using these commands - _sudo npm cache clean -f  _ _sudo npm install -g n_   _sudo n stable_.
Install Apache server - `sudo apt install apache2`  and start the services of Apache.

#Copy the files & directory of react into the Apache server.

Update the document root in the `sites-available` file.

#React server established on Apache server.

`Change domain name: first I used to login in third-party website for domain registration then I updated that domain in the Apache configuration file where I used the server name as my domain name and server alias also as the domain name then I gave the directory root.` 
Restart the Apache server now successfully able to connect with the react web app via domain name.

To provide SSL to my website, I used the Certbot website which provides commands for the Apache server to install the certificate: I followed the document and run commands to install the SSL certificate & after that, SSL lay on my react server.

#These are all configurations I have done for my POC1.
```

# Learning:
```sh
1. I have learned about react `libraries` and `dependencies`.
2. I did some troubleshooting while building the React app after I resolved those errors. This helped me to learn some new concepts about `react application`.
3. I learn some new things about the `Apache server`. I got differences between all the `Apache configuration files`. 
4. I got an idea about `DNS` & I configured a domain name for my server.
5. I learned new things that as `SSL security` and what is need of it.
```
