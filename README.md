Description
    This is a simple React project that demonstrates how to use CSS Grid to create a structured layout with different sections such as Header, Navigation, Article, Ads, and Footer.

Project Structure
    root/
    │-- src/
    │   │-- components/
    │   │   │-- Grid1.jsx
    │   │-- App.jsx
    │-- public/
    │-- index.css
    │-- package.json
    |-- package-lock.json
    │-- README.md

Usage
    1. Start the development server:
        npm run dev
    2. Open the browser and go to  http://localhost:5173/

Components
    App.jsx
        The main component that renders the Grid1 component.
    Grid1.jsx
        This component defines a grid layout with five sections:
        1. Header
        2. Navigation
        3. Article
        4. Ads
        5. Footer

Styling
The styles are defined in index.css using CSS Grid properties:
    grid-template-areas to define the layout structure
    grid-area to place elements accordingly
    gap, background-color, and padding for styling


Technologies Used
    React
    CSS Grid
    JavaScript