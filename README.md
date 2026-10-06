# YelpCamp

YelpCamp is a full-stack campground sharing web application where users can explore campgrounds, create their own campground listings, add reviews, and view campground locations on an interactive map.

## 🚀 Features

- User registration and login
- User authentication and authorization
- Create, edit, and delete campgrounds
- Add and delete campground reviews
- Interactive maps using Mapbox
- Campground image uploads using Cloudinary
- MongoDB database with Mongoose
- Flash messages for user feedback
- Form validation using Joi
- Secure user input handling
- Responsive UI using Bootstrap

## 🛠️ Technologies Used

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- Passport.js
- Express Session

### Frontend

- EJS
- Bootstrap
- CSS
- JavaScript

### APIs & Services

- Mapbox
- Cloudinary
- MongoDB Atlas

### Security

- Helmet
- Joi
- Sanitize HTML
- Express Mongo Sanitize

## 📂 Project Structure

```text
YelpCamp/
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── seeds/
├── utils/
├── cloudinary/
│
├── app.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/brahmjotsingh02/YelpCamp.git
```

### 2. Open the project

```bash
cd YelpCamp
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the project root and add:

```env
DB_URL=your_mongodb_connection_string
SECRET=your_session_secret
MAPBOX_TOKEN=your_mapbox_token
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret
```

Replace the placeholder values with your own credentials.

**Important:** Never upload your `.env` file to GitHub.

### 5. Start the application

```bash
node app.js
```

The application will run locally at:

```text
http://localhost:3000
```

## 🌐 Deployment

YelpCamp is deployed using the following services:

- **Render** — Web application hosting
- **MongoDB Atlas** — Cloud database
- **Mapbox** — Interactive maps and geolocation
- **Cloudinary** — Image storage

### Render Configuration

**Build Command:**

```bash
npm install
```

**Start Command:**

```bash
node app.js
```

### Environment Variables

The following environment variables should be added to Render:

```text
DB_URL
SECRET
MAPBOX_TOKEN
CLOUDINARY_CLOUD_NAME
CLOUDINARY_KEY
CLOUDINARY_SECRET
```

The actual values should be added securely through Render's Environment Variables settings.

### Automatic Deployment

The project is connected to GitHub and Render.

Whenever changes are pushed to the `main` branch, Render automatically builds and deploys the latest version of the application.

## 👨‍💻 Author

**Brahmjot Singh**

GitHub: https://github.com/brahmjotsingh02