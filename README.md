![image](https://github.com/user-attachments/assets/f8a971ff-4790-4bda-9c4f-d932d79ffa9f)# 💬 Snappy – Real-Time Secure Chat App

**Snappy** is a real-time messaging application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). It supports **user authentication**, **end-to-end encryption**, and a dynamic chat interface, designed for fast and secure communication.

## 🚀 Features

- 🔐 User Registration & Login
- 🧑‍🤝‍🧑 Real-Time Messaging (Socket.io)
- 🛡️ End-to-End Encryption (AES)
- 👤 Avatar Selection
- 🌙 Dark Mode UI
- 📱 Responsive Design for Mobile & Desktop

## 📸 App Screenshots

### 🔐 Login
[image](https://github.com/user-attachments/assets/88463065-418c-4a03-9c0c-63770ec46134)

### Sign-Up Pages
![image](https://github.com/user-attachments/assets/b14eb3a7-841d-44c6-8f80-10bdc6b6fcd3)


### 🧑‍🤝‍🧑 Chat Interface
![image](https://github.com/user-attachments/assets/303872c9-7338-47fb-9b24-6eef6844e196)


### 🖼️ Avatar Selection
![image](https://github.com/user-attachments/assets/3a7d705d-df67-47a6-bade-eabdf20a7bdf)


## 🛠️ Tech Stack

- **Frontend:** React.js, CSS (styled-components or Tailwind)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Real-Time:** Socket.io
- **Authentication:** JWT
- **Encryption:** AES (crypto-js)

### Installation

#### First Method
```shell
git clone 
cd chat-app-react-nodejs
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```
Done! Now open localhost:3000 in your browser.




