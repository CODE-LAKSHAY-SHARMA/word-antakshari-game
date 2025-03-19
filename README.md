# LAKSHAY SHARMA MCA 590010775 AIML Batch 01

# Word Antakshari Game

## Objective
The objective of this project is to develop a web-based Word Antakshari Game using **Node.js, Express.js, and MongoDB**. The game allows multiple rounds of gameplay, where each user must enter a meaningful word starting with the last letter of the previous word displayed by the system.

## Features
- Interactive word-based game with a dynamic UI.
- Backend implemented using **Node.js** and **Express.js**.
- Uses **MongoDB** as a database to store words.
- Real-time validation of words.
- Tracks score, time left, and streak.
- Error handling and user-friendly messages.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Installation and Setup
### Prerequisites
Make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Steps to Run the Project
1. **Clone the Repository**
   ```sh
   git clone https://github.com/lakshaysharma2001/word.game.git
   cd word-antakshari-game
   ```

2. **Install Dependencies**
   ```sh
   npm install
   ```

3. **Start MongoDB Server** (if not already running)
   ```sh
   mongod --dbpath /data/db
   ![image](https://github.com/user-attachments/assets/bab564c0-f85e-4307-8a8d-177c8206e709)

   ```

4. **Run the Server**
   ```sh
   node server.js
   ```
   The server will start on `http://localhost:27017`
   ![image](https://github.com/user-attachments/assets/7f348262-c535-42dc-bca0-1e8062ddd1dd)


6. **Run the Frontend**
   Open `index.html` in your browser or use Live Server in VS Code.

## File Structure
```
word-antakshari-game/
│── public/
│   ├── index.html        # Main frontend page
│   ├── styles.css        # Styling file
│   ├── game.js           # Game logic
│── models/
│   ├── Word.js           # MongoDB schema for storing words
│── server.js             # Backend server using Express.js
│── package.json          # Dependencies and scripts
│── README.md             # Documentation
```

## API Endpoints
| Method | Endpoint      | Description               |
|--------|--------------|---------------------------|
| GET    | /api/word    | Fetches a random word from the database |
| POST   | /api/word    | Validates and stores the user-submitted word |

## Screenshots
![image](https://github.com/user-attachments/assets/ccfff148-5593-418d-8d67-05dbedf7d54a)


## License
This project is open-source and available under the [MIT License](LICENSE).

