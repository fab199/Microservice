<h2>1. Introduction:</h2>

   - Application Name: EMart</b>
   - Architecture: Microservices
   - Front End: API Gateway with Nginx, Angular (client app)
   - Endpoints: root, /api, /webapi

<h2>2. Microservices:</h2>

   - Client App (Angular)</b>
   - Connected to /api served by NodeJS (Mart API)
   - Requires MongoDB Database (deployed as a container)
   - Web API:
   - Connects to /webapi served by Java (Books API)
   - Requires MySQL Database
   - All components (Nginx, Angular, NodeJS, Java, MongoDB, MySQL) run as containers.
   - 
<h2>3. Scalability and Flexibility:</h2>

   - Scalable from a developer's perspective.
   - Additional microservices (e.g., videos, payment gateway, cart) can be added.

<h2>4. Setting Up on Virtual Machine:</h2>

   - Utilizes Docker and Docker Compose.
   - Requires the EMart app repository.

<br/>
<img src="https://i.imgur.com/Rne9sZd.png" height="80%" width="80%" alt="steps to setting up virtual machine"/>
<br />

<h2>5. Steps for Setup:</h2>

   - Clone the EMart app repository.</b>
   - Open Docker Compose YAML file.
   - Run Docker Compose commands
   - Build images and run containers.

<br/>
<img src="https://i.imgur.com/3mfvAyA.png" height="80%" width="80%" alt="steps for setup"/>
<br />
<h2>Now the containers are running:</h2> <br/>
<img src="https://i.imgur.com/VPx0W4P.png" height="80%" width="80%" alt="containers"/>
<br />

<h2>6. Accessing the Application:</h2>

   - Access the application through the browser using the VM's IP address and port 80.</b>
   - Interact with the front end and register a user.
   - Demonstrates interaction with NodeJS (MongoDB) and Java (MySQL)

<h2>Copy the ip address of the VM:</h2> <br/>
<img src="https://i.imgur.com/yWvLnCv.png" height="80%" width="80%" alt="ip address"/>
<br />

<h2>access the application through the browser using the VM's IP address:</h2> <br/>
<img src="https://i.imgur.com/U4eQlNO.png" height="80%" width="80%" alt="application"/>
<br />

<h2>Interact with the front end and register a user(Register and Login):</h2> <br/>
<img src="https://i.imgur.com/Yieo75C.png" height="80%" width="80%" alt="to Sign up"/>
<br />
<br />
<img src="https://i.imgur.com/nK6KYAS.png" height="80%" width="80%" alt="to register"/>
<br />
<br />

<br/>
<img src="https://i.imgur.com/ZnmVfNw.png" height"80%" width="80%" alt="Login to the application"/>
<br />
<br />

That's Micro-service Application working on Docker platform
