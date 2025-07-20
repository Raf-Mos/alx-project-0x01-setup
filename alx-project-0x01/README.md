# ALX Project 0x01

A modern web application built with Next.js, TypeScript, and Tailwind CSS for managing posts and users.

## 🚀 Features

- **Posts Management**: View, create, edit, and delete posts
- **User Management**: Browse and interact with user profiles
- **Responsive Design**: Built with Tailwind CSS for optimal viewing on all devices
- **Modern UI**: Clean and intuitive user interface with modals and cards
- **TypeScript**: Full type safety throughout the application

## 🛠️ Tech Stack

- **Frontend Framework**: Next.js 14
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4
- **UI Components**: Custom React components
- **API Integration**: RESTful API services

## 📁 Project Structure

```
alx-project-0x01/
├── components/
│   ├── common/          # Reusable UI components
│   │   ├── Button.tsx
│   │   ├── Modal.tsx
│   │   ├── PostCard.tsx
│   │   ├── PostModal.tsx
│   │   ├── UserCard.tsx
│   │   └── UserModal.tsx
│   └── layout/          # Layout components
│       ├── Footer.tsx
│       └── Header.tsx
├── interfaces/          # TypeScript interfaces
│   ├── index.ts
│   └── types.ts
├── pages/               # Next.js pages
│   ├── index.tsx        # Home page
│   ├── posts/
│   │   └── index.tsx    # Posts page
│   └── users/
│       └── index.tsx    # Users page
├── services/            # API services
│   └── api.ts
└── styles/              # Global styles
    └── global.css
```

## 🚦 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd alx-project-0x01
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:3000`

## 📜 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint for code quality checks

## 🎨 UI Components

### Common Components
- **Button**: Reusable button component with various styles
- **Modal**: Generic modal component for overlays
- **PostCard**: Display individual posts in a card format
- **PostModal**: Modal for creating/editing posts
- **UserCard**: Display user information in a card format
- **UserModal**: Modal for user-related actions

### Layout Components
- **Header**: Navigation header with branding and menu
- **Footer**: Application footer

## 🔧 Configuration

### Tailwind CSS
The project uses Tailwind CSS for styling. Configuration can be found in `tailwind.config.js`.

### TypeScript
TypeScript configuration is available in `tsconfig.json` with strict type checking enabled.

### PostCSS
PostCSS configuration for processing CSS is in `postcss.config.js`.

## 📡 API Integration

The application integrates with external APIs through the `services/api.ts` file for:
- Fetching posts and user data
- Creating, updating, and deleting posts
- User management operations

## 🌐 Pages

- **Home (`/`)**: Landing page with navigation to posts and users
- **Posts (`/posts`)**: View and manage posts
- **Users (`/users`)**: Browse user profiles

## 🎯 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📄 License

This project is part of the ALX Software Engineering ProDev-Frontend program.


---

Built with ❤️ using Next.js and TypeScript
