# PassMate  
**Your Trusted Password Keeper**  

PassMate is a secure and user-friendly password manager built with React, Vite, Tailwind CSS, and MongoDB. This version of the project allows you to save, edit, and delete your site credentials, with passwords stored securely in a MongoDB database.  

---

## 🚀 Features  
- **Secure Password Storage**: Save your site credentials (site name, username, and password) in a MongoDB database.  
- **Edit and Delete Options**: Easily update or remove saved credentials.  
- **User-Friendly Interface**: Built with Tailwind CSS for a sleek and responsive design.  
- **Backend Integration**: Leverages a Node.js and Express backend for handling database operations.  
- **Data Security**: Ensures that sensitive data is stored securely in a database.  

---

## 🛠️ Tech Stack  
- **Frontend**: React  
- **Development Environment**: Vite  
- **Styling**: Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  

---

## 🔧 Installation  

### 1. Clone the Repository  
```bash  
git clone https://github.com/AbdullahShamoon/PassMate-mongo.git  
cd passmate-mongodb  
```

## 2. Install Dependencies
### For the Frontend
```bash
npm install  
```
### For the Backend
```bash
cd backend  
npm install  
```

## 3. Set Up Environment Variables
Create a .env file in the backend folder and configure the following:

```env
MONGO_URI=your_mongodb_connection_string  
PORT=5000  
```
## 4. Start the Development Servers
### Start the Backend Server
```bash
cd backend  
node --watch server.js
```
### Start the Frontend Server
Open a new terminal, navigate to the frontend folder, and run:
```bash
npm run dev  
```

## ✨ Usage
- Open the application.
- Enter the Site Name, Username, and Password in the input fields.
- Click the Save button to store the credentials in the MongoDB database.
- View and manage your saved credentials:
    - Edit: Update the details of any saved credential.
    - Delete: Remove credentials you no longer need.


## 📖 Future Enhancements
- Implement encryption for stored passwords.
- Introduce user authentication for better security.
- Add cross-browser support and synchronization options.

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## 🙌 Acknowledgments
Built with ❤️ using React, Vite, Tailwind CSS, Node.js, and MongoDB.
```vbnet
Let me know if this works or if you'd like further tweaks!
```