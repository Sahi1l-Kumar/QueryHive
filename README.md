<div align="center">
  <div>
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248" alt="mongodb" />
    <img src="https://img.shields.io/badge/-ShadCN_UI-black?style=for-the-badge&logoColor=white&logo=shadcnui&color=000000" alt="shadcnui" />
  </div>

  <h3 align="center">Query Hive</h3>

   <div align="center">
     A community-driven platform for asking and answering programming questions. Get help, share knowledge, and collaborate with developers from around the world. Explore topics in web development, mobile app development, algorithms, data structures, and more.
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. ⚙️ [Tech Stack](#tech-stack)
2. 🔋 [Features](#features)
3. 🤸 [Quick Start](#quick-start)

## <a name="tech-stack">⚙️ Tech Stack</a>

- Zod
- Next.js
- NextAuth
- Gemini API
- MongoDB
- ShadCN UI
- TypeScript
- TailwindCSS
- React Hook Form

## <a name="features">🔋 Features</a>

👉 **Authentication**: Secure sign-in with NextAuth, supporting Email/Password, Google, and GitHub.

👉 **Home Page**: Displays questions with filters, search, and pagination for easy navigation.

👉 **Recommendations**: Personalized suggestions on the home page.

👉 **Complex Layout**: Organized layout with popular questions and tags in view.

👉 **Question Details**: View questions with rich content, including images and code blocks.

👉 **Voting**: Upvote/downvote on questions to highlight helpful content.

👉 **View Counter**: Tracks the number of views for each question.

👉 **Bookmarking**: Save questions for quick access later.

👉 **Answer Posting**: MDX editor with light/dark modes for submitting answers.

👉 **AI Answer Generation**: Get AI-generated responses to questions.

👉 **Answer Filtering**: Sort answers by newest or most-voted, with pagination.

👉 **Answer Voting**: Upvote/downvote answers to rank quality responses.

👉 **Collections**: Organized saved questions with filters, search, and pagination.

👉 **Community**: Browse all users with search, filters, and pagination.

👉 **Profile**: View user info, badges, and engagement history with pagination.

👉 **Job Finder**: Discover jobs with filters and search, tailored to the user’s location.

👉 **Tags Page**: List of all tags with question counts, filters, and pagination.

👉 **Tag Details**: View questions by tag with search and pagination.

👉 **Ask a Question**: Simple interface for posting new questions.

👉 **Edit & Delete**: Update or remove questions and answers with validation and authorization.

👉 **Global Search**: Find content across questions, users, tags, and more.

👉 **Responsive Design**: Fully optimized for a seamless experience on desktops, tablets, and mobile devices.

👉 **High Performance**: Fast loading and smooth interactions for an efficient user experience.

and many more, including code architecture and reusability

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Sahi1l-Kumar/QueryHive.git
cd QueryHive
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
# Mongodb
MONGODB_URI=

# Gemini
GOOGLE_GENERATIVE_AI_API_KEY=

# Rapid API
NEXT_PUBLIC_RAPID_API_KEY=

# Auth
AUTH_GOOGLE_ID=
AUTH_GOOGLE_SECRET=
AUTH_GITHUB_ID=
AUTH_GITHUB_SECRET=
AUTH_SECRET=
NEXTAUTH_URL=

# Tiny Editor
NEXT_PUBLIC_TINY_EDITOR_API_KEY=

NEXT_PUBLIC_SERVER_URL=

NODE_ENV=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on the respective websites

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
