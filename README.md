# Repo Structure
```
project/
├── client/ # frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.jsx
│   │   │   ├── Footer.jsx
│   │   │   └── Button.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── About.jsx
│   │   │   └── Contact.jsx
│   │   ├── utils/
│   │   │   ├── api.js
│   │   │   └── helpers.js
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   └── icons/
│   │   ├── styles/
│   │   │   ├── global.css
│   │   │   └── theme.css
│   │   └── index.js
│   ├── public/
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   └── robots.txt
│   ├── package.json
│   └── README.md
│
├── server/ # Backend
│   ├── src/ 
│   │   ├── config/
│   │   │   ├── db.js
│   │   │   ├── dotenv.js
│   │   │   └── logger.js
│   │   ├── middleware/
│   │   │   ├── auth.js
│   │   │   └── errorHandler.js
│   │   ├── models/
│   │   │   ├── User.js
│   │   │   ├── Task.js
│   │   │   └── Index.js
│   │   ├── controllers/
│   │   │   ├── userController.js
│   │   │   ├── taskController.js
│   │   │   └── authController.js
│   │   ├── routes/
│   │   │   ├── userRoutes.js
│   │   │   ├── taskRoutes.js
│   │   │   └── authRoutes.js
│   │   ├── utils/
│   │   │   ├── emailSender.js
│   │   │   ├── jwtHelper.js
│   │   │   └── passwordHasher.js
│   │   └── server.js
│   ├── .env
│   ├── package.json
│   ├── README.md
│
├── model/ # AI 
│   ├── data/
│   │   ├── raw/
│   │   ├── processed/
│   │   └── README.md
│   ├── notebooks/
│   │   ├── exploration.ipynb
│   │   ├── training.ipynb
│   │   └── evaluation.ipynb
│   ├── src/
│   │   ├── models/
│   │   │   ├── model.py
│   │   │   ├── train.py
│   │   │   └── evaluate.py
│   │   ├── utils/
│   │   │   ├── data_loader.py
│   │   │   ├── preprocess.py
│   │   │   └── metrics.py
│   │   ├── main.py
│   │   └── requirements.txt
│   ├── README.md
│   └── Dockerfile
│
└── README.md
```
