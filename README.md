✅ Node.js Custom Server & Core Modules – Summary
🎯 Aim
To build a basic HTTP server using Node.js and explore built-in modules like os, path, and events.

📖 Description
This project highlights the power of Node.js core modules for server-side development without third-party frameworks. It introduces how to:

Create a custom HTTP server

Fetch OS-level details

Work with file paths

Use an event-driven architecture

It is a hands-on demo for backend fundamentals using only the Node.js standard library.

📁 Project Structure
pgsql
Copy code
node-server-demo/
├── server.js       # HTTP server with response
├── osInfo.js       # OS details using 'os' module
├── pathDemo.js     # Path manipulations using 'path' module
├── eventDemo.js    # Event handling with 'events' module
├── README.md       # Project documentation
🔧 Core Modules Used
http – Creates the web server.

os – Retrieves system info (platform, CPU, memory).

path – Manages file/directory paths.

events – Demonstrates event emit/listen mechanism.

🛠️ Installation & Setup
Prerequisites:

Node.js installed

VS Code or any code editor

How to Run:

bash
Copy code
cd node-server-demo      # Navigate to project folder
code .                   # Open in VS Code
node server.js           # Start HTTP server (localhost:3000)
node osInfo.js           # Run OS info script
node pathDemo.js         # Run path module demo
node eventDemo.js        # Run events demo
💡 Sample Output
server.js – Browser shows: "Hello from Node.js custom server!"

osInfo.js – Logs: platform, memory, uptime, CPU info

pathDemo.js – Logs: file name, extension, path joining

eventDemo.js – Logs: "Hello, Alice!" from custom event handler

📜 License
Released under the MIT License – free for use, modification, and distribution.
![image](https://github.com/user-attachments/assets/f1aef7ca-229c-469b-a044-c5b6c51ec380)
![image](https://github.com/user-attachments/assets/a3b263dc-087f-4eae-9d3f-9db30c1c6e5a)
![image](https://github.com/user-attachments/assets/fc28ca7f-8d95-4583-b0a7-5c9b3323fe3a)
![image](https://github.com/user-attachments/assets/de6f3c78-da6e-427a-9dd4-4aa7a1390b0f)
![image](https://github.com/user-attachments/assets/6bb2dd31-6d12-4bb7-a1ca-15a90ff18680)
![image](https://github.com/user-attachments/assets/255d119c-4f2a-4204-9667-87b8ab232b7f)




