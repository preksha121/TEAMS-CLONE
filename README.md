# TEAMS-CLONE

A video chat web app with basic features of video and audio calling for more than two users (preffered upto 4).

  

# Tech Stack

- [Node.js](https://nodejs.org/en/)
- [Socket.io](https://socket.io/)
- [Web RTC](https://github.com/webrtc)
- [Heroku](https://dashboard.heroku.com/)

# Features

- Video Calls
- Mute audio/video
- Instantly join a video call with a code
- Chat in real-time
- Chat Notifications
- Unlimited duration calls
- Collaborative Whiteboard
- Screensharing

# Demo

Check out the live demo: [demo-link](https://hydro-mountie-72396.herokuapp.com/)

  

# How to run

1. Clone this repository:- `git clone https://github.com/preksha121/TEAMS-CLONE`
2. go to he directory:- `cd TEAMS-CLONE`
3. Install dependencies:- `npm install`
4. Start the Server:- `npm start`
5. Open two browsers on your laptop and point them `localhost:3000`. If you want to use a client on another computer/mobile, make sure you publish your server on an HTTPS connection (otherwise the camera may not work).
6. Click on `create room`button if you are the host, else enter the room id.
7. That's it!!

  

# Note

1. The video **may not** be seen if the host and remote user are on different operating systems/browsers **(Google Chrome preferred)**.
2. You can create a free [xirsys](https://xirsys.com/) account and use their free ice server. Add config file in parent directory containing the code.