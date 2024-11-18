# Medium Clone

A feature-rich Medium clone application with a backend deployed on **Cloudflare Workers** using the **Hono** framework, and a frontend built with **React-TypeScript** using the Vite@latest template. This project also includes a published **npm package** containing reusable code from the `common` folder.

## Features

- **Backend**: Deployed on Cloudflare Workers, leveraging the lightweight and performant Hono framework.
- **Frontend**: Developed using React, TypeScript, and Vite for a seamless developer experience and blazing-fast builds.
- **Reusable Code**: Core functionalities extracted into a published npm package for reusability.
- **Medium Clone Functionalities**:
  - User authentication (sign up, sign in, and sign out)
  - Write, edit, and delete articles
  - Read articles from various authors
  - Like and comment on articles
  - Follow/unfollow users
  - Personalized feed for authenticated users

## Tech Stack

- **Frontend**:
  - React
  - TypeScript
  - Vite
- **Backend**:
  - Cloudflare Workers
  - Hono framework
- **Package Manager**: npm
- **State Management**: Recoil (optional if used)
- **Routing**: React Router DOM

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v18+)
- npm or yarn
- Cloudflare Workers CLI (`wrangler`)
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/medium-clone.git
   cd medium-clone ```

2. Install dependencies for the frontend:
   ```bash
   cd frontend
   npm install```
   
3.Install dependencies for the backend:

  ```bash
  Copy code
  cd backend
  npm install
```

4. Install the npm package :

    ```bash
    Copy code
    npm install @kushallunkad/common
    ```
    
### Development

#### Frontend

Start the frontend development server:

   ```bash
   cd frontend
   npm run dev
   ```

#### Backend
 Start the backend :
  ```bash
   cd backend
   npm run dev
    ```
