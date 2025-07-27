# MongoDB-Atlas-Project-BookNexus-Online-Bookstore

MongoDB Data Modeling
Collections:

books: Contains all book records

customers: Stores customer information

orders: Embeds basic book info and references customer by customer_id

Data Modeling Style:

Embedding is used for order's book items (fast retrieval).

Referencing is used between orders → customers (modularity and reuse).

