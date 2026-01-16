# Requirements

## Functional Requirements

FR-01: The system must allow user management, including the creation and administration of users with different roles (for example, cashier, stock clerk, and administrator).

FR-02: The system must allow product registration, including basic information such as name, sale price, cost, category, minimum stock, and status (active/inactive).

FR-03: The system must allow viewing the complete list of registered products.

FR-04: The system must allow viewing detailed information for an individual product.

FR-05: The system must allow modifying the information of an existing product.

FR-06: The system must allow deactivating products without physically deleting them, in order to preserve historical information for reports and queries.

FR-07: The system must allow recording product entries into inventory (restocking).

FR-08: The system must allow consulting the current inventory of products.

FR-09: The system must generate alerts when a product’s stock is equal to or below the defined minimum stock level.

FR-10: The system must allow registering a sale.

FR-11: The system must allow adding one or more products to a sale, specifying the quantity for each product).

FR-12: The system must validate product stock availability before confirming a sale.

FR-13: The system must automatically calculate the total amount of the sale.

FR-14: The system must allow recording the payment method used for the sale (for example, cash or card).

FR-15: The system must allow confirming and finalizing a sale.

FR-16: The system must automatically deduct inventory when a sale is confirmed.

FR-17: The system must allow canceling a sale and reverting inventory changes.

FR-18: The system must allow generating sales reports by time period.

FR-19: The system must allow generating reports of best-selling products.

FR-20: The system must allow calculating and visualizing estimated profit based on sale price and product cost.

## Non-Functional Requirements

NFR-01: The system must provide a simple and intuitive user interface designed for daily use in a commercial environment.

NFR-02: The system must be efficient and respond quickly to common operations, especially during the sales process.

NFR-03: The system must ensure data consistency, preventing sales when there is insufficient stock.

NFR-04: The system must be reliable and minimize information loss in the event of errors or system failures.

NFR-05: The system must allow operation traceability by preserving sales history and inventory movement records.

NFR-06: The system must be scalable, allowing future incorporation of new modules or functionalities.

NFR-07: The system must include basic access control mechanisms based on user roles.
