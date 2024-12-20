Sure, here's your content converted into GitHub README markdown format:

```markdown
# CodeAnt AI: Frontend Developer Intern Assignment

## Project Overview

**CodeAnt AI** is a Y Combinator-backed startup that's transforming the world of code quality and security. By leveraging cutting-edge AI-driven solutions, CodeAnt AI offers efficient and deterministic fixes that enhance the security and cleanliness of code. Trusted by industry leaders and supported by top investors, CodeAnt AI aims to solve complex challenges and push the boundaries of coding innovation.

---

## Setting Up the Project Locally

To run the project on your local machine, follow these steps:

### 1. Clone the Repository

Use the following commands to clone the repository and navigate into the project directory:

```bash
git clone https://github.com/smasoom/Assignment-CodeAntAI.git
cd Assignment-CodeAntAI
```

### 2. Install Dependencies

Install the required dependencies using pnpm:

```bash
pnpm install
```

### 3. Start the Development Server

After installing the dependencies, start the development server with:

```bash
pnpm run dev
```

The app will be available at [http://localhost:5173](http://localhost:5173).

## Technologies Used

- **ReactJS**: For building the user interface.
- **TypeScript**: For adding static typing and improving code quality.
- **Tailwind CSS**: For utility-first styling and rapid UI development.
- **Vite**: For fast development and build processes.

## Features

- Fully responsive design, optimized for different screen sizes.
- Accurate implementation of the Figma design.
- Clean and modular code for scalability and maintainability.

## React + TypeScript + Vite

This project uses Vite as the bundler, and React is set up with TypeScript for an enhanced development experience.

### Vite Configuration

- **Fast Development**: Vite provides fast development and build capabilities.
- **Hot Module Replacement (HMR)**: For smooth development.
- **React Plugin**: Uses `@vitejs/plugin-react` to enable fast refresh for React.

### ESLint Configuration

To maintain code quality, ESLint is configured with TypeScript. Below are some details:

1. **Enable Type-Aware Linting Rules**
   - Configure the `parserOptions` property in ESLint.
   - Add `eslint-plugin-react` to enforce React-specific linting rules.

2. **Sample Configuration**

```javascript
import react from 'eslint-plugin-react';

export default tseslint.config({
  settings: { react: { version: '18.3' } },
  plugins: { react },
  rules: {
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
});
```

## License

This project is licensed under the MIT License. For more details, see the LICENSE file.
```
