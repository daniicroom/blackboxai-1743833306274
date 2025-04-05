
Built by https://www.blackbox.ai

---

# Resume Website

## Project Overview

The Resume Website is a web application built using Next.js, React, and TypeScript. It serves as a digital representation of a resume, showcasing skills, projects, and experiences. The application is designed to be responsive, user-friendly, and visually appealing, utilising modern web development practices.

## Installation

To get started with this project, follow the steps below to clone the repository and install the necessary dependencies.

### Prerequisites

- Node.js (>= 18.18.0)
- npm (Node package manager)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/resume-website.git
   cd resume-website
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

Once the dependencies are installed, you can start the development server using:

```bash
npm run dev
```

This will start the Next.js development server, typically accessible at `http://localhost:3000`. You can view the application in your browser.

To build the application for production, run:

```bash
npm run build
```

To start the production server, run:

```bash
npm run start
```

## Features

- **Responsive Design**: The website adjusts well for desktop and mobile views.
- **TypeScript Support**: Provides type safety and error checking.
- **Modern Development Stack**: Built using React, Next.js, and Tailwind CSS for styling.
- **Clean Architecture**: Organized project structure for maintainability.
- **Linting**: Includes linting for code quality checks.

## Dependencies

The project relies on a set of dependencies defined in `package.json`:

- `@types/react`: Type definitions for React.
- `@types/react-dom`: Type definitions for ReactDOM.
- `clsx`: Utility for constructing className strings conditionally.
- `cmdk`: A command menu component for React.
- `lucide-react`: A collection of customizable icons for React.
- `next`: The React framework for production.
- `react`: JavaScript library for building user interfaces.
- `react-dom`: Provides DOM-specific methods for React.
- `tailwind-merge`: Utility for merging Tailwind CSS class names.
- `typescript`: A superset of JavaScript that compiles to clean JavaScript output.

### Dev Dependencies

- `@types/node`: Type definitions for Node.js.

## Project Structure

The project follows a standard structure for Next.js applications:

```
resume-website/
├── node_modules/        # Project dependencies
├── public/              # Static assets
├── src/                 # Application source code
│   ├── components/      # Shared components
│   ├── pages/           # Next.js Pages
│   ├── styles/          # CSS styles and Tailwind configuration
│   └── utils/           # Utility functions
├── .gitignore           # Specifies intentionally untracked files to ignore
├── next-env.d.ts        # TypeScript definitions for Next.js
├── package.json         # Project metadata and dependencies
├── package-lock.json    # Exact versioning of dependencies
├── tsconfig.json        # TypeScript compiler configuration
└── README.md            # Project documentation
```

Feel free to modify any of the components or styles to better suit your personal preferences or portfolio needs!

## Contributing

If you'd like to contribute to the project, please fork the repository and create a pull request. All contributions are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

--- 

This README.md provides a comprehensive overview of the Resume Website project. For further information or questions, please don't hesitate to reach out!