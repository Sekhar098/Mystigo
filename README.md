# Mystigo 🌍

Your compass to the world's best-kept secrets and offbeat destinations.


## 📖 Introduction

**Mystigo** is a full-stack travel discovery web app designed to help adventurous users explore hidden gems and offbeat destinations around the world. It moves beyond typical tourist spots, offering a platform to discover, share, and explore unique locations with dynamic content, interactive maps, and real-time data integration.

<br>

## 🚀 Live Demo & Screenshots

Check out the live version of the project here: **[Live Demo Link](https://sekhar-mystigo.onrender.com/)**

<div align="left">
  <em>A glimpse of the Mystigo application in action.</em>
</div>

---

## ✨ Key Features

- 🧭 **Explore the Unexplored:** Navigate our interactive maps and uncover hidden gems that mainstream guides won’t show you.

- 🎨 **Immersive Visuals:** Dive into destinations with stunning images, detailed descriptions, and authentic user reviews that bring every location to life.

- 🔒 **Rock-Solid Security:** Enjoy personalized experiences with secure sign-ups and logins powered by JWT (JSON Web Tokens).

- ☁️ **Cloud-Powered Uploads:** Instantly share your adventure photos—Cloudinary keeps them safe and fast.

- ✨ **Be a Trailblazer:** Add your favorite spots, tell your story, and inspire other explorers with your own contributions.

- 📐 **Seamless Across Devices:** Mystigo looks and works flawlessly on desktops, tablets, and phones—plan your adventure anywhere, anytime.

---

## 🛠️ Tech Stack

* **Frontend:** React.js, React Router, Axios, CSS3
* **Backend:** Node.js, Express.js, JWT, Bcrypt.js
* **Database:** MongoDB, Mongoose
* **Services:** Cloudinary (Image Storage), Geoapify (Mapping)

---

## ⚙️ Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Before running Mystigo locally, make sure you have the following installed:

* [Node.js](https://nodejs.org/) (v18.x or later)
* [Git](https://git-scm.com/)
* [MongoDB](https://www.mongodb.com/) — either a local instance or a cloud-hosted database
* A package manager like [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

Follow these steps to get Mystigo running locally:

1. **Clone the repository**
    ```bash
    git clone https://github.com/Sekhar098/Mystigo.git
    cd Mystigo
    ```

2. **Install dependencies**
    ```bash
    npm install
    ```

3. **Set up environment variables**
    Create a `.env` file in the root directory and add the following variables:

    ```bash
    # Server & Database
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    CORS=*

    # JWT Secrets
    ACCESS_TOKEN_SECRET=your_super_secret_access_token
    ACCESS_TOKEN_EXPIRY=1d
    REFRESH_TOKEN_SECRET=your_super_secret_refresh_token
    REFRESH_TOKEN_EXPIRY=10d
    
    # Cloudinary API Keys
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    CLOUDINARY_URL=your_cloudinary_url

    # Geoapify API Key
    GEOAPIFY_API_KEY=your_geoapify_api_key
    ```

4. **Run the application**
    ```bash
    npm run dev
    ```
    Open your browser and go to: `http://localhost:5000`

---

## 💡 Usage

After following the installation steps, open your browser and navigate to `http://localhost:5000`. You can register for a new account, log in to an existing one, browse the map for hidden gems, view destination details, and contribute by adding new places you've discovered.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 👤 Author : **Sekhar Gauda**

* **GitHub:** [Sekhar Gauda](https://github.com/Sekhar098)
* **LinkedIn:** [Sekhar Gauda](https://linkedin.com/in/sekhargauda) 

---

## 📜 License

This project is licensed under the [MIT License](LICENSE.md). See the file for more details.
