
## 🎉 Mingley
Welcome to Mingley, a unique social networking platform designed for seamless interaction and community building! Whether you're looking to make new friends, foster connections, or join interest-based groups, Mingley is your go-to solution. Built with a robust backend and a dynamic frontend, Mingley aims to redefine how people interact digitally. 🌍💬


## 🌟 Project Description
Mingley is a modern and user-friendly social networking application built to facilitate conversations, groups, and networking across a broad range of interests. The platform is designed with a mobile-first approach, ensuring accessibility and ease of use across devices.

Mingley focuses on:

 • Engagement: Enabling meaningful conversations between users.

 • Customizable Profiles: Create profiles that showcase your      interests.

 • Interest Groups: Join or create groups to share content and discussions with like-minded people.

 • Real-Time Communication: Chat with friends or group members in real time.

 • Security: We prioritize the safety and privacy of user data with built-in security measures.

## ✨ Features

•User Registration & Authentication: Secure sign-up and login functionality using JWT or OAuth2.

•Custom Profiles: Add personal information, interests, and profile pictures to make yourself stand out.

•Groups and Communities: Create and join groups based on interests or topics.

•Real-Time Messaging: Chat in real time with friends or group members using WebSockets.

•Post Sharing & Liking: Share text, images, and content in groups, and let others engage with your posts.

•Mobile-Friendly UI: Designed with a mobile-first approach, ensuring accessibility across devices.

•Search Functionality: Find users, groups, and topics easily.
## 📋 Requirements

Follow these steps to set up Mingley on your local machine:

1. Clone the repository
```bash
git clone https://github.com/princid/Mingley.git
```
2. Navigate to the project directory
```bash
cd Mingley
```
3. Install dependencies for both frontend and backend

    • For backend
    ```bash
    cd backend
    npm install
    ```
    • For frontend
    ```bash
    cd frontend
    npm install
    ```
4. Set up your environment variables
Create a .env file in the backend directory with the following:
```bash
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```
5. Start the backend server
```bash
npm run server
```
6. Start the frontend development server
```bash
npm run start
```
7. Open your browser and navigate to http://localhost:3000 to see Mingley in action!



## 🚀 Usage

Once the project is running, explore the following key areas:

• User Authentication: Sign up or log in to start interacting with other users.

• Profile Management: Customize your profile by adding pictures, interests, and more.

• Groups: Join existing groups or create new ones to find others who share your interests.

• Real-Time Messaging: Start conversations and chat with other members of the platform.

• Content Sharing: Post updates, share images, and engage with other users’ content.


## 🔍 Example Commands

Here are some useful commands for developing and managing the project:

• Run backend server:
```bash
npm run server
```
• Run frontend
```bash
npm start

```
• Build for production (frontend):
```bash
npm run build

```
• Run tests (if applicable):
```bash
npm test

```


## 🌐 API Integration

Mingley uses a custom API for the backend built with Express and MongoDB. Here’s how you can extend or interact with the API:

• User Authentication API: Manages login, sign-up, and token generation.

• Group Management API: Endpoints to create, join, and interact with groups.

• Post API: Allows users to share posts within groups and handle likes, comments, etc.


Sample API usage for fetching posts:
```bash
GET /api/posts
Authorization: Bearer <your_token>
```



## 🗓 Last Updated

This project was last updated on 10/10/24. As Mingley evolves, we are committed to keeping the platform updated with new features, bug fixes, and performance improvements.
## 🎨 Design Philosophy

Mingley's design is centered around:

•Clarity: An intuitive, clean interface that’s easy to navigate.

•Community: Features that foster real connections and meaningful discussions.

•Scalability: A modular design that grows as our user base expands.

We believe that good design is key to building a successful social platform.
## 💡 Contributing

Contributions are welcome! If you’d like to contribute, feel free to fork the repository, create a new branch, and submit a pull request. Before doing so, please check the existing issues to avoid duplicating efforts.
## 📄 License

This project is licensed under the MIT License. For more information, see the [LICENSE](https://github.com/AbhishekU007/Mingley/blob/main/LICENSE) file.


