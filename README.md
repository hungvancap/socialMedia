# socialMedia
A social media web app with basic functionalities that I created after following the instruction from a Youtube video.


# Screenshots:
![image](https://github.com/hungvancap/socialMedia/assets/51280437/99d920b2-c2e4-4e5e-b95e-6dc12857ed64)
![image](https://github.com/hungvancap/socialMedia/assets/51280437/85028081-7163-475d-90e6-c1a35d297dfc)
![image](https://github.com/hungvancap/socialMedia/assets/51280437/da7653cc-6e5b-4d42-8ab0-eb9f16c079af)

# Features:
- Sign up, log in, log out
- Create posts
- Like and unlike posts
- Toggle dark/light mode

# How to run locally:
1. Clone the code
3. Create a .env file with MONGO_URL, JWT_SECRET, and PORT variables
4. cd into /server
5. run "npm i express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose"
6. run "node index.js"
7. cd into /client with a new terminal
8. run "npm i react-redux @reduxjs/toolkit redux-persist react-dropzone dotenv formik yup react-router-dom@6 @mui/material @emotion/react @emotion/styled @mui/icons-material"
9. run "npm run start"
