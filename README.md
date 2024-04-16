# Zotion

![image](https://github.com/RandomThacker/zotion/assets/141705990/d6e42733-9426-466e-b7a1-76222d567c4c)


Zotion is a Notion-like application built with Next.js 14, React, Convex, Tailwind, Clerk, and EdgeStore. It is a real-time database and Notion-style editor that allows you to create, edit, and delete documents. It also allows you to publish your note to the web.

It uses Convex as the backend, which is a real-time database that allows for instant data updates. The application also uses Edgestore, a distributed key-value store, to manage the images and files uploaded by the users.The user authentication is handled by Clerk, a secure and scalable user authentication API.

## Live

Zotion - [https://zotion-app.vercel.app/](https://zotion-app.vercel.app/)

## Features

-Real-time database 🔗

-Notion-style editor 📝

-Light and Dark mode 🌓

-Infinite children documents 🌲

-Trash can & soft delete 🗑

-Authentication 🔐

-File upload

-File deletion

-File replacement

-Icons for each document (changes in real-time) 🌠

-Expandable sidebar ➡🔀⬅

-Full mobile responsiveness 📱

-Publish your note to the web 🌐

-Fully collapsable sidebar ↕

-Landing page 🛬

-Cover image of each document 🖼

-Recover deleted files 🔄📄

## Technologies

![NextJS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Shadcn-ui](https://img.shields.io/badge/shadcn/ui-000000.svg?style=for-the-badge&logo=shadcn/ui&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC.svg?style=for-the-badge&logo=Tailwind-CSS&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF.svg?style=for-the-badge&logo=Clerk&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-ee342f.svg?style=for-the-badge&logo=Convex&logoColor=white)
![Edgestore](https://img.shields.io/badge/Edgestore-a57fff.svg?style=for-the-badge&logo=Edgestore&logoColor=white)

## Installation

1. Clone the repository
2. Install the dependencies

```
npm install
```

3. Set up the environment variables

```
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

4. Run Convex

```
npx convex dev
```

5. Run the development server

```
npm run dev
```

