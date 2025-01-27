# Match Me App 💕

A full-stack dating application built with Next.js 14, Prisma, NextAuth, Pusher, and Cloudinary. 🌐✨

## Features 🌟

- **Real-Time Messaging** 📨: Leverages Pusher to enable real-time chat functionality.
- **User Authentication** 🔐: Powered by NextAuth for secure login and registration.
- **Profile Customization** 🖼️: Users can upload and edit profile images via Cloudinary.
- **Advanced Form Handling** 📝: Utilizes React Hook Form and Zod for seamless user input validation.
- **State Management** ⚙️: Managed efficiently with Zustand for a responsive user experience.

## Tools 🛠️

- Next.js 14 🚀
- Prisma 📊
- NextAuth (Auth.js) 🔒
- Pusher 📡
- Cloudinary ☁️
- Vercel 🌍
- PostgreSQL 🐘
- React Hook Form 🎣
- Zod Validation ✅
- Zustand 🧠
- TypeScript 🖥️

## Prerequisites 📋

- Node.js (v18 or higher) 🟢
- PostgreSQL database 🐘

## Installation ⚙️

1. Clone the repo: 🖥️

   ```bash
   git clone https://github.com/BernieTv/Dating-App-with-NextJS.git
   cd Dating-App-with-NextJS
   ```

2. Install packages: 📦

   ```bash
   npm install
   ```

3. Set up environment variables in a `.env` file. 🛠️ Example:

   ```env
   DATABASE_URL=your_postgresql_connection_string
   NEXTAUTH_SECRET=your_nextauth_secret
   PUSHER_APP_ID=your_pusher_app_id
   PUSHER_KEY=your_pusher_key
   PUSHER_SECRET=your_pusher_secret
   PUSHER_CLUSTER=your_pusher_cluster
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   ```

4. Set up Prisma database: 🗂️

   ```bash
   npx prisma generate
   npx prisma migrate dev
   npx prisma db seed
   ```

5. Run the development server: 🚀

   ```bash
   npm run dev
   ```

## Deployment 🌍

1. Deploy to Vercel by linking your repository. 🔗
2. Add the necessary environment variables in the Vercel dashboard. 🛠️
3. Build and deploy the application. 🚀

## Contributing 🤝

1. Fork the repository. 🍴
2. Create a new branch (`git checkout -b feature/YourFeatureName`). 🌿
3. Commit your changes (`git commit -m 'Add some feature'`). 📝
4. Push to the branch (`git push origin feature/YourFeatureName`). 📤
5. Open a pull request. 📨

## License 📜

This project is licensed under the MIT License. 🪪 See the `LICENSE` file for details.

