# Pizza Menu
The Pizza Menu project is a simple React application that displays a list of pizza items for a fictional pizza company, "Fast React Pizza Co." The app dynamically displays the menu items, highlights when a pizza is sold out, and includes a footer that informs customers whether the shop is currently open for orders.

## Features
- Pizza Menu Display: The application dynamically lists pizzas, including their name, ingredients, and price.
- Sold Out Pizzas: Pizzas that are sold out are clearly marked and styled.
- Opening Hours: The app checks the current time and displays an "Order" button if the pizza shop is open.
- Responsive Design: The app layout is styled for a good user experience.

## Components
The project is structured with the following React components:

- App: The main component that renders the entire application.
- Header: Displays the company name.
- Menu: Lists the pizza options. If no pizzas are available, it shows a message.
- Pizza: Renders an individual pizza item, showing the photo, name, ingredients, price, or "SOLD OUT" message if applicable.
- Footer: Shows whether the shop is open or closed based on the current time.
- Order: Displays an order button and information when the shop is open.

## Display
![image](https://github.com/user-attachments/assets/c4d747de-265f-4ecc-9713-326093d77a44)

## Installation
To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/uhpoler/PizzaMenu.git
   ```
2. Install the dependencies:
   ```bash
      npm install
   ```
3. Start the application:

   ```bash
      npm start
   ```
