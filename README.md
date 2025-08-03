# Fast React Pizza Co.

A simple React app that displays a pizza menu. Built as part of a React learning project.

<img width="1913" height="907" alt="image" src="https://github.com/user-attachments/assets/54711fce-d6db-4025-95bb-cb67171f29c3" />


## Features

- View a menu of 6 delicious pizzas with images, ingredients, and prices.
- Sold out pizzas are clearly marked.
- Dynamic footer shows if the restaurant is open or closed based on the current time.
- Clean, responsive UI.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone this repository or download the source code.
2. Navigate to the project directory:

   ```bash
   cd 03-pizza-menu
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

### Running the App

Start the development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Project Structure

- `src/index.js` – Main React application file.
- `src/index.css` – App styles.
- `public/pizzas/` – Pizza images.

## Customization

- To add or modify pizzas, edit the `pizzaData` array in `src/index.js`.
- To change opening hours, update the `openingTime` and `closingTime` variables in the `Footer` component.

## License

This project is for educational purposes only.
