# ALX Listing App

ALX Listing App is a property listing platform inspired by Airbnb's listing page. This application allows users to view property details in a structured and interactive manner. The app is built with Next.js, TypeScript, and TailwindCSS, following best practices for scalability and reusability.

## Project Structure

The project is organized into the following main directories:

```
├── components
│   └── common
│       ├── Card.tsx          # Reusable Card component for property display
│       └── Button.tsx        # Reusable Button component for actions
│
├── interfaces
│   └── index.ts              # TypeScript interfaces for component props
│
├── constants
│   └── index.ts              # Application-wide constants (URLs, config, UI text)
│
├── public
│   └── assets                # Public assets like images, icons, etc.
│
├── pages
│   └── index.tsx             # Main application entry point
│
└── README.md                 # Project documentation
```

### Directories Overview

- **components/**: Contains all reusable UI components like Card and Button.
- **interfaces/**: Defines TypeScript interfaces for strong typing and error reduction.
- **constants/**: Holds constant values such as API URLs, configuration settings, and UI text.
- **public/assets/**: Stores static assets such as images and icons.

## Getting Started

Follow these steps to run the project locally:

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory:**

   ```bash
   cd alx-listing-app
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Run the development server:**

   ```bash
   npm run dev
   ```

5. **Open your browser at:**
   [http://localhost:3000](http://localhost:3000)

You should now be able to see the ALX Listing App running locally.

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.
