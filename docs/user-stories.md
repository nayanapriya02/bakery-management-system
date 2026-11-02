Project-wide rule (write it once at the top): every page works on phone and desktop.

Items

1. Add item (Must). As an admin, I want to add a new item with a name, price, and starting stock, so that it can be sold.

The “Add item” form needs name, price, and stock.
The form refuses empty names and prices of 0 or less.
After saving, the new item appears in the items list.

2. Edit item (Must). As an admin, I want to edit an item’s name or price, so that the information stays correct.

Clicking “Edit” opens the item’s current details.
Saving updates the list immediately.
A price change affects new sales only, not past ones.

3. View items (Must). As an admin, I want to see all items with their prices and stock, so that I know what the bakery sells.

The Items page lists name, price, and stock for every item.
An item with 0 stock is clearly marked “Out of stock”.

4. Delete item (Should). As an admin, I want to remove an item I no longer sell, so that the list stays clean.

Clicking “Delete” asks me to confirm first.
The item disappears from the list after confirming.
Inventory

5. Low-stock view (Must). As an admin, I want low-stock items highlighted, so that I know what to bake or buy soon.

Items at or below a set low level (for example 5) are highlighted.
The Inventory page can show only low-stock items.

6. Adjust stock (Should). As an admin, I want to correct an item’s stock, so that records match what’s really on the shelf (for example, after spoilage).

I can set a new quantity for an item.
The change appears immediately in the inventory list.
Sales

7. Build a sale (Must). As a cashier, I want to pick items and quantities for a sale, so that I can serve a customer.

I can add an item to the current sale and set its quantity.
Adding the same item again increases its quantity.
I can remove a line from the sale.

8. Sale totals (Must). As a cashier, I want to see each line total and the grand total, so that I can tell the customer the price.

Line totals and the grand total update immediately when quantities change.
An empty sale shows a total of 0, and the “Save sale” button is disabled.

9. Save sale (Must). As a cashier, I want to save a sale, so that it’s recorded and the stock goes down.

Saving records the sale with the date and time.
Each sold item’s stock goes down by the quantity sold.
I can’t sell more than the stock available, and I’m shown a clear message.

10. Sales history (Should). As an admin, I want to see past sales and their details, so that I can check what was sold.

A list shows date, sale number, and total.
Clicking a sale shows its items and quantities.
Dashboard and login

11. Dashboard (Must). As an admin, I want a dashboard with today’s key numbers, so that I see how the bakery is doing at a glance.

It shows today’s total sales amount and the number of sales.
It shows how many items are low on stock.

12. Login (Should). As an admin, I want to log in with a username and password, so that only authorized people can use the system.

Opening any page without logging in sends me to the login page.
A wrong password shows an error and doesn’t log me in.
A “Log out” button ends my session.