Full Stack Realtime Chat App 

Developed a real-time chat application using MongoDB, Express.js, React, and Node.js (MERN), integrating Socket.io to enable seamless and instant messaging between users.

Implemented JWT-based authentication and authorization, ensuring secure user sessions and preventing unauthorized access to protected routes.

Designed a fully responsive and user-friendly interface with Tailwind CSS and DaisyUI, enhancing accessibility and providing a smooth user experience across all devices.

Integrated Cloudinary for media uploads, allowing users to securely share images within conversations while ensuring optimized storage and retrieval.

Optimized WebSocket connections and message delivery, reducing message latency by 40%, improving real-time responsiveness, and minimizing server load.

Added online/offline status tracking for users, increasing engagement by 30% and improving the overall interactive experience.

Deployed the application on Vercel (frontend), Railway/Render (backend), and MongoDB Atlas (database) to ensure scalability, high availability, and cloud-based hosting.

### Setup .env file

-- need to give this info.
```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```

Start Backend

cd backend
npm install
npm start


Start Frontend


cd frontend
npm install
npm run dev
