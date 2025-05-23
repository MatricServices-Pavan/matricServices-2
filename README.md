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


## Additional Services

### MongoDB Setup
- This project uses MongoDB as the database.
- You can run MongoDB locally or create a free cluster on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
- To connect MongoDB Atlas with this backend:
  1. Create an Atlas cluster.
  2. Create a database user with password.
  3. Whitelist your IP address.
  4. Copy the connection string (URI).
  5. Add the URI to your environment variables as `MONGO_URI`.

### Image Uploads and Management
- Image uploads are handled using [Multer](https://github.com/expressjs/multer) for receiving files.
- For image hosting and optimization, we use [ImageKit](https://imagekit.io/):
  1. Create an account on ImageKit.
  2. Get your public API key, private API key, and URL endpoint.
  3. Store these keys securely in environment variables:
     - `IMAGEKIT_PUBLIC_KEY`
     - `IMAGEKIT_PRIVATE_KEY`
     - `IMAGEKIT_URL_ENDPOINT`
  4. Use ImageKit SDK or API to upload images.


### Backend Deployment link:

https://matricservices.onrender.com/api

