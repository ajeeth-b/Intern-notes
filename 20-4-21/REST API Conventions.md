# REST API Conventions

- use proper noun as path
- use different method for different operation with same name
	- **EXAMPLE**
		- PUT /customers
		- GET /customers
- use dynamic URL for specifc data
	- **EXAMPLE**
		- GET /customers/1
		- GET /customers/2
- use query in URI for specifc data or order byb
	- **EXAMPLE**
		- GET /customers?sorted-by=id
- use subcollection if required
	- **EXAMPLE**
		- GET /customers/1/orders
