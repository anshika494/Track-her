<a name="readme-top"></a>

<div align="center">
  <h1 align="center">Stree</h1>
  <p align="center">
    <strong>Empowering Women's Safety and Growth</strong>
    <br />
    A comprehensive platform for reporting incidents, accessing resources, and building community.
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#key-features">Key Features</a></li>
    <li><a href="#tech-stack">Tech Stack</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

Track-Her is a dedicated platform designed to enhance women's safety through community-driven reporting and resource sharing. It provides a secure environment for women to anonymously report incidents, visualize safety data on interactive maps, and connect with supportive tech communities.

### Project Gallery
![Screenshot 2024-09-01 140429](https://github.com/user-attachments/assets/6dfe5973-6268-4c9c-9d12-9620aff816fc)
![Screenshot 2024-09-01 140457](https://github.com/user-attachments/assets/23593768-3dd0-4ec0-8150-5d58ea2edefe)
![f5deba14-507b-4560-9efb-ad277085036d](https://github.com/user-attachments/assets/5a332933-9256-4bb2-9902-fb98e791ca93)
![Screenshot 2024-09-01 140820](https://github.com/user-attachments/assets/fbb0f040-b22f-461b-9270-7e12f40671e3)
![Screenshot 2024-09-01 140947](https://github.com/user-attachments/assets/8858c2b3-7c7f-4aa9-9d3f-cbe31ce40b7b)
![Screenshot 2024-09-01 141134](https://github.com/user-attachments/assets/fa77b0ed-0570-45e0-a2f3-7c7f8438b555)

## Key Features

- **Anonymous Reporting**: Safely report incidents without compromising personal identity.
- **Interactive Safety Map**: Visualize reported incidents to identify safe and unsafe zones using Leaflet.
- **Resource Hub**: Access curated guidance on tech communities, helplines, and educational resources.
- **Admin Dashboard**: Comprehensive management tools for users, incidents, and contacts.
- **Community Forum**: Connect and share experiences with other women in a safe space.
- **Emergency Helplines**: Quick access to vital emergency contact information.

## Tech Stack

### Frontend
- **Framework**: React.js (Vite)
- **State Management**: Recoil
- **Routing**: React Router DOM
- **Mapping**: Leaflet & React-Leaflet
- **Styling**: Tailwind CSS & MDB React UI Kit
- **HTTP Client**: Axios

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Authentication**: JWT & Bcrypt.js
- **Validation**: Zod
- **File Handling**: Multer

## Getting Started

### Prerequisites
- Node.js (v16.0.0 or higher)
- MongoDB account/instance

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/anshika494/Track-her
   cd TrackHer
   ```

2. **Backend Setup**
   ```bash
   cd server
   npm install
   # Create .env file with:
   # MONGO_URI, JWT_SECRET_KEY, FRONTEND_URL, PORT
   ```

3. **Frontend Setup**
   ```bash
   cd ../client
   npm install
   # Create .env file with:
   # VITE_BACKEND_URL
   ```

## Usage

1. **Start Backend**
   ```bash
   cd server
   npm run dev
   ```

2. **Start Frontend**
   ```bash
   cd client
   npm run dev
   ```

## Contributing

Contributions make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

