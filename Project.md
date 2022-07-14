**PROJECT 3 DOCUMENTATION**

As usual, i logged into my instance using AWS to create a virtual PC screenshot below

![alt text](./Images/Log%20into%20Ubuntu%20Server.png)

I then updated Ubuntu using the code `sudo apt update` with screenshot below

![alt text](./Images/Sudo%20apt%20Update.png)

I also upgraded Ubuntu with the code `sudo apt upgrade` with screenshot below

![alt text](./Images/Sudo%20apt%20upgrade.png)

I then proceeded to get the location of the Node.js software on the server using `curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -` with screenshot confirmation below

![alt text](./Images/Location%20of%20Nodejs.png)

This was then followed by installing Node.js with the code `sudo apt-get install -y nodejs` and the confirmation below

![alt text](./Images/Nodejs%20installation.png)

I then confirmed the node version using and confirmed with the screenshot below.

![alt text](./Images/Node%20version%20confirmation.png)

I then created a To-do directory for the Project MERN with confirmation gotten below followed by the creation of the package.json file

![alt text](./Images/Create%20Todo%20project%20directory%20and%20initiate%20package.png)

I then installed Expressjs, Dotenv and updated all files with required content

![alt text](./Images/Expressjs%20installation.png)
![alt text](./Images/install%20dotenv.png)
![alt text](./Images/Update%20expressjs%20content.png)

I then started the Node server using the code `node index.js` and got the confirmation below

![alt text](./Images/Start%20node%20server.png)

I also updated the security group to allow inbound access using port 5,000

![alt text](./Images/Allow%20access%20throw%20port%205000.png)

I then called the public ip using port 5,000 to get the confirmation page below.

![alt text](./Images/Confirmation%20of%20express%20created.png)

I then created Routes which would all with **POST**, **GET** **DELETE** commands

![alt text](./Images/Create%20Routes%20and%20api%20doc.png)

I then installed Mongoose which will serve as my Database using the code `npm install mongoose`

![alt text](./Images/Install%20Mongoose.png)

I then connected my Mongodb page to my terminal using the connect code

![alt text](./Images/Connect%20to%20MOngodb.png)

I then picked my IP which is configured to access the created API to run some commands on Postman. I ran a POST commang with screenshot below

![alt text](./Images/Post%20confirmation.png)
![alt text](./Images/Get%20confirmation.png)

I then proceeded to create a frontend page using React. I used the code `npx create-react-app client`

![alt text](./Images/create-react-app%20client.png)

In the Todo directory, i also ran some commands; `npm install concurrently --save-dev` & `npm install nodemon --save-dev` Confirmation in the screenshot shown below

![alt text](./Images/install%20concurrently.png)

![alt text](./Images/install%20nodemon.png)

I then updated necessary files with the right configuration where necessary. I then updated the security group to allow access for 3000 port

![alt text](./Images/Add%20port%203000%20inbound%20rule.png)

I then went on to install Axios using the code `npm install axios` 

![alt text](./Images/install%20axios.png)

I then restarted my instance, started my node and connected to the API using port 3000 and got the final page confirming the front end creation

![alt text](./Images/Todo%20page.png)

**THANK YOU**
