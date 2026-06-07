This is a project made for messaging with people securely

# Project F Chatting - Server

### Folder Structure 
```
Project_F_Chatting/
│
├── Project_F_Chatting/                    # React Frontend
│   ├── public/
│   │
│   ├── src/
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   ├── icons/
│   │   │   └── fonts/
│   │   │
│   │   ├── components/
│   │   │   ├── shared/
│   │   │   ├── navbar/
│   │   │   └── footer/
│   │   │
│   │   ├── layouts/
│   │   │   ├── MainLayout.tsx
│   │   │   ├── DashboardLayout.tsx
│   │   │   └── AuthLayout.tsx
│   │   │
│   │   ├── pages/
│   │   │   ├── Home/
│   │   │   ├── Login/
│   │   │   ├── Register/
│   │   │   ├── Dashboard/
│   │   │   └── NotFound/
│   │   │
│   │   ├── routes/
│   │   │   ├── router.tsx
│   │   │   ├── PrivateRoute.tsx
│   │   │   └── AdminRoute.tsx
│   │   │
│   │   ├── hooks/
│   │   │   ├── useAuth.ts
│   │   │   └── useAxiosSecure.ts
│   │   │
│   │   ├── context/
│   │   │   └── AuthProvider.tsx
│   │   │
│   │   ├── services/
│   │   │   ├── authService.ts
│   │   │   └── api.ts
│   │   │
│   │   ├── utils/
│   │   │   ├── formatDate.ts
│   │   │   └── validators.ts
│   │   │
│   │   ├── App.tsx
│   │   └── main.tsx
│   │
│   └── package.json
│
├── backend/                            # Express.js Server
│   │
│   ├── src/
│   │   ├── config/
│   │   │   └── db.js
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── middlewares/
│   │   ├── services/
│   │   ├── utils/
│   │   └── app.js
│   │
│   ├── server.js
│   ├── .env
│   ├── package.json
│
├── .gitignore
├── README.md
└── package.json
```