# Team Orbit 🚀

### Jira Clone – Collaborative Team & Project Management App

Team Orbit is a collaborative project management application inspired by Jira.  
It enables teams to manage workspaces, projects, tasks, and members efficiently with real-time cloud database support.

This project was developed as a college final-year project.

---

## ✨ Features

- 🔐 Authentication (Email, Google, GitHub OAuth)
- 🏢 Workspace Management
- 📁 Project Creation & Organization
- ✅ Task Management with Status Tracking
- 👥 Member Roles (Admin / Member)
- 📅 Due Dates & Task Positioning
- 🖼 Image Upload Support
- 📊 Analytics Dashboard
- 📱 Responsive UI

---

## 🛠 Tech Stack

- **Next.js 14**
- **React 18**
- **TypeScript**
- **Appwrite (Backend as a Service)**
- **Tailwind CSS**
- **React Query**
- **Hono**
- **Vercel (Deployment)**

---

## 📂 Project Structure

jira-clone/
├── src/
│ ├── app/
│ ├── components/
│ ├── features/
│ ├── hooks/
│ ├── lib/
│ └── config/
├── public/
├── .env.example
├── package.json
└── next.config.mjs

---

## ⚙️ Environment Setup

Create a `.env.local` file in the root directory:

NEXT_PUBLIC_APP_BASE_URL=http://localhost:3000
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=YOUR_PROJECT_ID
NEXT_APPWRITE_KEY=YOUR_SECRET_KEY

NEXT_PUBLIC_APPWRITE_DATABASE_ID=YOUR_DATABASE_ID
NEXT_PUBLIC_APPWRITE_MEMBERS_ID=YOUR_COLLECTION_ID
NEXT_PUBLIC_APPWRITE_PROJECTS_ID=YOUR_COLLECTION_ID
NEXT_PUBLIC_APPWRITE_TASKS_ID=YOUR_COLLECTION_ID
NEXT_PUBLIC_APPWRITE_WORKSPACES_ID=YOUR_COLLECTION_ID
NEXT_PUBLIC_APPWRITE_IMAGES_BUCKET_ID=YOUR_BUCKET_ID

yaml
Copy code

> ⚠️ Do not commit `.env.local` to GitHub.

---

## 🚀 Installation

```bash
npm install
npm run dev
App will run on:

arduino
Copy code
http://localhost:3000
☁️ Deployment
This project is optimized for deployment on Vercel.

Make sure to configure all environment variables in Vercel before deploying.

📜 License
This project is licensed under the MIT License.

🙏 Acknowledgement
This project is inspired by an open-source Jira clone implementation available under a free-to-use license.
The architecture and learning references were adapted for educational purposes.

👨‍💻 Author
Prasad Ghorpade
Computer Science Student
```
