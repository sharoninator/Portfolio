<h1>JWipe - Disk Sanitization</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This project is a demonstration tool for common website exploits. It allows you to run a website with very common vulnerabilities, and demonstrates the exploits that can be used against them. The exploit is deployed and the user can see how it works, and can read more about how to patch the vulnerability. This project demonstrates the following vulnerabilities:

 - Default credentials
 - Insecure design
 - Path Traversal
 - Software and Data Integrity Failures
 - Security Logging and Monitoring Failures


<h2>Languages and Utilities Used</h2>

- <b>Node.JS</b> 
- <b>Express.JS</b>

<h2>Description</h2>
Install and launch the program with the following commands:

```bash
git clone https://github.com/sharoninator/Website-Security-Tool.git
cd Website-Security-Tool/
npm install
node app.js
```
You can open the application by going to http://localhost:3001 in a web browser.

(Optional) Run Juice shop to use the last two exploits:

```bash
git clone https://github.com/sharoninator/juice-shop.git
sudo docker buildx build -t my-juice-shop .
sudo docker run -p 3000:3000 my-juice-shop
```

<h2>Program walk-through:</h2>

<p align="center">
Installing and Launching the program: <br/>
<img src="https://github.com/user-attachments/assets/2a97c1c7-fef6-419f-984e-a8842c3d4750" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Running the default credentials exploit:  <br/>
<img src="https://github.com/user-attachments/assets/cd1aa5d2-ef99-4ba1-bc16-20f2f8e13d0e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Running the path traversal exploit: <br/>
<img src="https://github.com/user-attachments/assets/17247d69-0cd3-4e72-b9c2-15b41ce5d7d1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Running the insecure design exploit:  <br/>
<img src="https://github.com/user-attachments/assets/8b3e2595-958d-4f42-87de-b4a85abf19a3" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
