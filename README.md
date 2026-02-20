# Google Forms Clone

A simple web application that mimics the functionality of Google Forms, built with Next.js, TypeScript, and Tailwind CSS.

## Features

- Create and edit forms with various question types
- Question types: Short answer, Paragraph, Multiple choice, Checkboxes, Dropdown
- Mark questions as required
- Fill out forms
- View submitted responses in a table

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```

2. Run the development server:
   ```
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- Use the main page to build your form.
- Click "View Form" to see and fill out the form.
- Click "View Responses" to see all submitted responses.

Data is stored in localStorage for simplicity.

## Deployment to Netlify

1. Build the project for static export:
   ```
   npm run build
   ```

2. The `out` folder will contain the static files.

3. Upload the `out` folder to Netlify for hosting.