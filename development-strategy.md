# Budget-App: development strategy

Building this site one step at a time

## 0. Setup

- Create `development-strategy.md`
- Create `readme.md`
- Create `index.html`
- Create `shared-content\assets`
- Create `shared-content\style`
- Create `controllers\event-listeners.js`
- Create `view-models\user-interface.js`

## 1. User Story: Add-budget-Balance

**A user can add value for a budget balance .**

### DOM & styles

- Edit both `shared-content\style` and `shared-content\assets`, to add necessary assets and css styles.
- Create an input and a button for add budget in `index.html`.

### `view-models\user-interface.js`

- Create a listener for `submit` action for div form `budget-form`.

### `controllers\event-listeners.js`

- Create function `submitBudgetForm()` to submit budget value.
- Create function `showBalance()` to reflect balance values.

## 2. User Story: Add-Expense

**A user can add expense which has a value and an amount**

### DOM & styles

- Edit both `shared-content\style` and `shared-content\assets`, to add necessary assets and css styles.
- Create an input and a button for add budget in `index.html`.

### `view-models\user-interface.js`

- Create a listener for `submit` action for div form `expense-form`.

### `controllers\event-listeners.js`

- Create function `submitExpenseForm()` to submit expense value and amount.
- Create function `addExpense(expense)` to reflect expense values and amounts.

## 3. User Story: Edit-Delete-Expense

**A user can edit/delete a previously added expense**

### DOM & styles

- Edit both `shared-content\style` and `shared-content\assets`, to add necessary assets and css styles.
- Create an input and a button for add budget in `index.html`.

### `view-models\user-interface.js`

- Create a listener for `click` action for div `expense-list`.

### `controllers\event-listeners.js`

- Create function `editExpense()` to edit expense value and amount.
- Create function `deleteExpense()` to delete expense value and amount.
- Create function `totalExpense()` to reflect expense values and amounts.

## 5. Complete README.md

- Complete `README.md` for more details about the project.
