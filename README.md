# 🏡 HavenHub

HavenHub is a full-stack vacation stay listing platform built using **Node.js, Express.js, MongoDB, and EJS**. It provides a centralized platform where users can browse vacation stays, create and manage their own property listings, upload images, and share reviews securely.

---

## ✨ Features

- 🔐 User Authentication using Passport.js
- 🏠 Create, Update, and Delete Listings
- 🔍 Search Listings by Country
- ⭐ Add Reviews and Ratings
- ☁️ Image Upload using Cloudinary
- 📍 Location Integration using Mapbox
- 💾 Session Management with MongoDB
- ⚡ Flash Messages and Error Handling
- 📱 Responsive User Interface

---

## 🛠️ Tech Stack

### Frontend
- EJS
- HTML
- CSS
- JavaScript
- Bootstrap

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- Passport.js
- Express Session
- Connect-Mongo

### Cloud Services
- Cloudinary
- Mapbox

### Validation
- Joi

---

## 📂 Project Structure

```
HavenHub/
│── controllers/
│── models/
│── routes/
│── views/
│── public/
│── utils/
│── init/
│── app.js
│── middleware.js
│── cloudConfig.js
│── schema.js
│── package.json
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Navigate to the Project Folder

```bash
cd HavenHub
```

### Install Dependencies

```bash
npm install
```

---

## 🔑 Environment Variables

Create a **.env** file in the root directory and add the following:

```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_secret_key

CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_secret

MAP_TOKEN=your_mapbox_access_token
```

---

## ▶️ Run the Project

Start the development server:

```bash
node app.js
```

---

## 🌐 Open in Browser

```
http://localhost:8080/listings
```

---


## 📄 License

This project is developed for educational and academic purposes.
