# HarmonyHive
<img width="632" alt="image" src="https://github.com/Avtech04/tempppp/assets/97428742/52b28889-ad3c-4128-bc6b-9a8b61aa0496">


HarmonyHive is a pioneering platform enabling individuals and organizations to donate excess food seamlessly, fostering sustainable consumption and aiding in natural and human disasters worldwide. Through intuitive interfaces, users can contribute via Google Pay, while NGOs facilitate distribution to those in need, ensuring efficient and transparent relief efforts. With real-time tracking and admin authentication, HarmonyHive stands at the forefront of compassionate and effective humanitarian initiatives.

## Technologies and Product Used

- [Google Pay](https://nextjs.org/): Used Google Pay to ensure seamless and secure Payment.

- [Google Translate](https://nextjs.org/): Used Google Translate to ensure multi lingual facility.

- [Map Box Api](https://nextjs.org/): Used Map box api to ensure visual representation of map and routes.

- [Node.js](https://nodejs.org/): A JavaScript runtime built on Chrome's V8 JavaScript engine.

- [Socket.io](https://socket.io/): A library for real-time web applications. It enables real-time, bidirectional, and event-based communication.

- [MongoDB](https://www.mongodb.com/): A NoSQL database for storing and managing data.

## Features

### 1. Multiplayer Drawing and Guessing
![image](https://github.com/samjain233/doodle/assets/94921996/1c098b7e-e2f3-4c3c-a62d-f89ab0da6d0c)

- Experience real-time drawing and guessing with friends or other players.
- One player draws a word while others try to guess it.

### 2. Multiplayer Support
- Enjoy multiplayer functionality, allowing users to join public rooms or create private ones.
- Invite friends using unique links for a seamless gaming experience.

### 3. In-Game Chat
- Communicate with other players through an in-game chat feature.
- Enhance the gaming experience with real-time conversations.

### 4. User Authentication and Profile Management
![image](https://github.com/samjain233/doodle/assets/94921996/9a20ed34-e243-42c6-8789-808b905e0b2e)

- Create personalized profiles and track your game history.
- User can be authenticated using google, discord and github.

### 5. Drawing Tools
![image](https://github.com/samjain233/doodle/assets/94921996/24cad121-e2da-4e24-a76c-5116107d7958)

- Choose from different pen colors and brush sizes.
- Utilize features like eraser, bucket fill, and color picker.

### 6. Save Current Drawing
- Save your masterpiece at any point during the drawing session.

### 7. Room Administration
![image](https://github.com/samjain233/doodle/assets/94921996/18fcdf6c-b06a-4eef-8208-492d53498ba7)

- Assign a user as the room admin with the power to kick users and make others admins.
- Chat restrict a user without kicking them for better moderation.

### 8. Undo and Redo
![image](https://github.com/samjain233/doodle/assets/94921996/8040ac1d-b7da-4a8e-b743-25cc1036c731)

- Enjoy the flexibility of undoing and redoing recent drawing operations.

### 9. Profanity Filter
![image](https://github.com/samjain233/doodle/assets/94921996/cde02f16-cd81-43cd-b6fe-4f1508b8d421)

- Maintain a friendly environment with a profanity filter in the chat.

### 10. Drawing Shapes
![image](https://github.com/samjain233/doodle/assets/94921996/36990f94-bef5-4ad8-a39c-13a3a909e288)

- Explore creativity with the ability to draw various shapes, including circle, square, rectangle, ellipse, free draw, and lines.

## Getting Started

To get started with the Real-Time Drawing and Guessing Web App, follow these steps:

1. Clone the repository.
```bash
  git clone https://github.com/Avtech04/GDSC.git
```


2. Go to the project directory

```bash
  cd GDSC
```

3. Go to the frontend project directory
   
```bash
  cd solution
```

4. Install dependencies

```bash
  npm install
```

5. Creating .env file
```node

REACT_APP_MAP_KEY=  // mapbox api key (link: https://www.mapbox.com/)

```
6. Start the server in development mode

```bash
  npm start
```

7. From main folder GDSC go to backend directory (in another terminal)

```bash
  cd server
```

8. Install dependencies

```bash
  npm install
```

9. Creating .env file
```node

ClientId= //google id for goolge auth
ClientSecret= //google client secret
```

10. Connect to MongoDB By changing the file server/db/conn.js as per convinence

11. Start the backend server
```bash
  nodemon app.js
```

