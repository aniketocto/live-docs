
## ⚙️ Tech Stack
- Next.js
- TypeScript
- Liveblocks
- Lexical Editor
- ShadCN
- Tailwind CSS


## 🔋 Features

 👉 Authentication: User authentication using GitHub through NextAuth, ensuring secure sign-in/out and session management.

 👉 Collaborative Text Editor: Multiple users can edit the same document simultaneously with real-time updates.

 👉 Documents Management

- Create Documents: Users can create new documents, which are automatically saved and listed.
- Delete Documents: Users can delete documents they own.
- Share Documents: Users can share documents via email or link with view/edit permissions.
- List Documents: Display all documents owned or shared with the user, with search and sorting functionalities.
 👉 Comments: Users can add inline and general comments, with threading for discussions.

👉 Active Collaborators on Text Editor: Show active collaborators with real-time presence indicators.

 👉 Notifications: Notify users of document shares, new comments, and collaborator activities.

 👉 Responsive: The application is responsive across all devices.

and many more, including code architecture and reusability


## ⚡ Quick Start

Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:
- [git](https://git-scm.com/)
- [node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)


## Cloning the Repository

```bash
git clone https://github.com/aniketocto/live-docs
cd SmartDocs
```

## Installation

Install the project dependencies using npm:

```bash
npm install
```

Set Up Environment Variables

Create a new file named `.env` in the root of your project and add the following content:

```
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

## ⚡ Quick Start

Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:
- [git](https://git-scm.com/)
- [node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)


## Cloning the Repository

```bash
git clone https://github.com/aniketocto/live-docs
cd SmartDocs
```

## Installation

Install the project dependencies using npm:

```bash
npm install
```

Set Up Environment Variables

Create a new file named `.env` in the root of your project and add the following content:

```
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```
Replace the placeholder values with your actual [Clerk](https://clerk.com/) & [LiveBlocks](https://liveblocks.io/) credentials. You can obtain these credentials by signing up on the Clerk and LiveBlocks website.


Running the Project

```
npm run dev
```

Open http://localhost:3000 in your browser to view the project.



