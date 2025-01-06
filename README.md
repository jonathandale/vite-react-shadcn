# React + TypeScript + Vite + Shadcn + Tailwind

A minimal boilerplate for a React app with TypeScript, Vite, Tailwind CSS, and Shadcn UI components.

## Features

- **React** for building user interfaces.
- **TypeScript** for type-safe development.
- **Vite** for blazing-fast builds and development.
- **Tailwind CSS** for utility-first styling.
- **Shadcn UI** for customizable and reusable components.

## Getting Started

### 1. Create a New Project

Use [degit](https://github.com/Rich-Harris/degit) to clone this repository as a template:

```bash
$ npx degit jonathandale/vite-react-shadcn my-new-project
```

### 2. Install Dependencies

Navigate to the project directory and install the required dependencies:

```bash
$ cd my-new-project
$ npm install
```

### 3. Configure Tailwind & Shadcn

Before adding Shadcn components, customize the following configuration files to suit your project's needs:

- **`components.json`**: Define your component structure.
- **`tailwind.config.js`**: Adjust Tailwind settings, themes, and plugins.

### 4. Adding Shadcn Components

Use the Shadcn CLI to add components to your project. For example:

```bash
$ npx shadcn@latest add button
```

You can explore and install more components as needed.

### 5. Development

Start the development server:

```bash
$ npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) to view your app.
