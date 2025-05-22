#  Matric Services – Backend

Welcome to the Matric Services Backend repository!  
This backend supports the Matric Services frontend platform and manages:

- Workshop and product data  
- User authentication (via JWT)  
- File uploads (via Multer)   
- Admin access and role-based routes  


## Tech Stack Used

- Runtime: Node.js  
- Framework: Express.js  
- Database: MongoDB (Mongoose ODM)  
- Authentication: JSON Web Token (jsonwebtoken)  
- File Uploads: Multer  
- Middleware: CORS, Express JSON, JWT Auth Middleware  



##  Steps to Run This Project Locally

### 1. Clone the Repository

git clone https://github.com/your-username/matricServices-2.git

cd matricServices-2


### 2. Install Dependencies

npm install


### 4. Start the Server

nodemon index.js


## Development Tips

- Use Postman to test secured endpoints  
- Ensure MongoDB is running locally or connected via cloud (MongoDB Atlas)  
- Store uploaded files in the uploads/ folder  
- Use the `authMiddleware` for protecting routes  
- Cleanly separate logic into `controllers/` and `routes/` for scalability  


### Backend Deployment link:

https://matricservices.onrender.com/api

