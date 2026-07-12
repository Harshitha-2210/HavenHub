# HavenHub

HavenHub is a full-stack vacation stay listing platform built using Node.js, Express.js, MongoDB, and EJS. It allows users to browse listings, add new properties, edit their own listings, and post reviews securely.

## Features

- User authentication using Passport
- Create, update, and delete listings
- Search listings by country
- Add reviews and ratings
- Image upload using Cloudinary
- Location support using Mapbox
- Session management with MongoDB
- Flash messages and error handling

## Tech Stack

- **Frontend:** EJS, HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** Passport.js
- **Image Upload:** Cloudinary
- **Validation:** Joi
- **Maps:** Mapbox

## Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd project
npm install

## Environment Variables
Create a .env file and add:

ATLASDB_URL=your_mongodb_connection_string
SECRET=your_secret_key
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_secret
MAP_TOKEN=your_mapbox_token

Run the Project
node app.js

Open in browser:
http://localhost:8080/listings

