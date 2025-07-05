# twi-ctf-p


To start Project - step by step -


Requirements
Node.js
1-Download and install from: https://nodejs.org/

npm
- Comes with Node.js by default.

2-XAMPP
For running Apache and MySQL locally.
Download from: https://www.apachefriends.org/

3-ngrok
To expose your local server to the internet.
Download from: https://ngrok.com/download

----------------------------------------------- ---  

Setup Instructions
Install dependencies:
Open your terminal in the project folder and run:

Start XAMPP:

Open XAMPP Control Panel.
Start both Apache and MySQL.
Update ngrok URL in your files:

Find the variable like const API = 'https://xxxx.ngrok-free.app' in all project files (e.g., challenge1.html, challenge2.html, etc.).
Replace it with your current ngrok URL.
Run ngrok:

In your terminal, run:
(Replace 3001 with your server port if different.)
Copy the generated ngrok URL and use it as described above.
Start your server:

------------------------------------------------------------

npm init -y
npm install express
ngrok http 3001
node index.js
