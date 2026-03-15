cd server
npm install
npm start
Then open:



Run on iPhone (HTTPS)
iOS motion sensors often require HTTPS. Use Cloudflare Tunnel:

cloudflared tunnel --url http://localhost:3000
Open the generated https://*.trycloudflare.com link on the phone, then tap Enable Motion Sensors.

Tech
Node.js HTTP server serving /public

WebSocket server (ws) for real-time broadcast

p5.js for visualisation

iPhone DeviceMotion / DeviceOrientation input

Author
Fanhao Kong (fkong002@gold.ac.uk)
