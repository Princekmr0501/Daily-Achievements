## How an HTTPS Request Works

Example: Clicking a Product on Amazon
* When a user clicks on a product on Amazon, the following steps take place:

* User Action: The user clicks on a product on the Amazon website or app.

* URL Generation: The browser generates a URL corresponding to that product page.

* HTTPS Request: The browser sends an HTTPS request (e.g., using fetch) to the server.

* Request Sent to CDN: The request first reaches a CDN (Content Delivery Network). The CDN  checks whether the requested data is available in a nearby data center.

* Cache Check: If the data is cached, the CDN returns the response immediately. If not, the request is forwarded to the main server.

* Server Processing: The server receives the request and forwards it to the appropriate API.

* API & Database Interaction: The API checks permissions and business logic, then requests data from the database.

* Database Response: The database sends the requested product data back to the API.

* Response Formatting: The API converts the data into JSON format.

* Response to Client: The JSON response is sent back to the browser.

* UI Rendering: The browser renders the product details on the screen.

## How APIs Work
* What is an API?
An API (Application Programming Interface) is a medium that allows two software systems to communicate with each other.

* Users cannot directly access the database.

* APIs act as a secure bridge between the client and the database.

## Real-World Examples of APIs
* Posting on Quora
When a user posts a question or answer on Quora:

The data is sent to Quora’s API

The API validates the request

The data is stored in the database

The post becomes visible to other users

This is done using CRUD operations:

Create → Add a new post

* Liking a Comment on Instagram
When a user likes a comment:

An API call is made

The API updates the like count in the database

The updated count is returned

The number changes automatically on the UI

This uses:

Update → Modify existing data