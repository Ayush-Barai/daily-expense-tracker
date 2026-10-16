# Daily Expense Tracker

A lightweight, responsive expense tracker that helps you record and review daily spending directly in your browser.

## Features

- Add an expense name, amount, and category.
- Choose from `Food`, `Travel`, `Shopping`, or `Other`.
- View the running total of all recorded expenses.
- See the number of saved expenses.
- Delete individual expenses.
- Validate required names and positive amounts.
- Persist expenses with browser `localStorage`.
- Use the tracker on desktop and mobile screen sizes.

## Getting Started

No build tools or dependencies are required.

1. Clone or download this repository.
2. Open [index.html](./index.html) in a modern web browser.
3. Start adding expenses.

For a more consistent local development experience, serve the folder with any static file server and open the provided local URL.

## How to Use

1. Enter a description in **Expense name**.
2. Enter an amount greater than `$0`.
3. Select a category.
4. Click **Add Expense**.
5. Review the total and expense list.
6. Click **Delete** beside an expense to remove it.

## Data Storage

Expenses are stored locally in the browser under the `daily-expense-tracker-expenses` `localStorage` key. No backend or external service is used, so:

- Data stays on the device and browser where it was entered.
- Data is not synchronized between browsers or devices.
- Clearing browser site data removes the saved expenses.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage`

## Project Structure

```text
daily-expense-tracker/
├── index.html
└── README.md
```

## License

No license has been specified for this project yet.
