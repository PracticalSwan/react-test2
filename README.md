# React Card Component Practice

This project demonstrates creating and using reusable React components with styling.

## What I Learned

### 1. Creating Reusable Components
- Built a `Card` component that displays profile information
- The component is self-contained and can be reused multiple times
- Each card includes an image, title, and description text

### 2. Component Composition
- Used the `Card` component multiple times in the `App` component
- Demonstrated how to render the same component repeatedly using JSX
- Shows the power of component reusability in React

### 3. JSX and HTML-like Syntax
- Created card structure using JSX elements (`div`, `img`, `h2`, `p`)
- Used `className` instead of `class` for CSS styling
- Added the `alt` attribute for image accessibility

### 4. Component Structure
The `Card` component includes:
- **Image**: Profile picture from an external URL
- **Title**: Person's name
- **Description**: Personal information text

### 5. CSS Styling
- Applied CSS classes to style the card components:
  - `card`: Container styling
  - `card-image`: Image styling
  - `card-title`: Title styling
  - `card-text`: Description text styling

## Project Structure

- `App.jsx`: Main component that renders multiple `Card` components
- `Card.jsx`: Reusable card component with profile information

## Key Concepts

- **Component Reusability**: Same component used multiple times without rewriting code
- **Component-Based Architecture**: Breaking UI into independent, reusable pieces
- **JSX Syntax**: Writing HTML-like code in JavaScript
- **CSS Integration**: Styling components using className attributes
