------------------------------------------------------------------------
# Interactive-Apparel E-store

## Overview
Interactive-Apparel E-store is an engaging e-commerce platform tailored for clothing enthusiasts. Crafted using JavaServer Pages (JSP), Servlets, and MSSQL, this project is designed to deliver a fluid and enjoyable shopping experience for users seeking the latest apparel trends.

## Features
- Intuitive interface for seamless browsing and purchasing of clothing items.
- Responsive and interactive pages driven by JSP, ensuring a dynamic user experience.
- Servlets managing backend processes, including user authentication, cart management, and order fulfillment.
- MSSQL database integration for efficient storage and retrieval of product information.

## Project Structure
```
Interactive-Apparel E-store
|-- src
|   |-- main
|       |-- java
|           |-- com
|               |-- sarojgiri
|                   |-- estore
|                       |-- servlets
|                           |-- AuthenticationServlet.java
|                           |-- ShoppingCartServlet.java
|                       |-- model
|                           |-- Product.java
|                       |-- util
|                           |-- DatabaseConnector.java
|-- web
|   |-- WEB-INF
|       |-- views
|           |-- index.jsp
|           |-- product.jsp
|           |-- cart.jsp
|           |-- order.jsp
|       |-- web.xml
|   |-- index.jsp
|   |-- product.jsp
|   |-- cart.jsp
|   |-- order.jsp
|   |-- css
|       |-- style.css
|   |-- js
|       |-- script.js
```

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/SarojGiri/Interactive-Apparel E-store.git
   ```
2. Configure your MSSQL database and update `DatabaseConnector.java` with the connection details.
3. Deploy the project on a Servlet container (e.g., Apache Tomcat).
4. Access the application at `http://localhost:8080/Dynamic-Fashion-Estore`.

## Author
This project was crafted by Saroj Giri.

## Technologies Used
- JavaServer Pages (JSP)
- Servlets
- MSSQL

## License
This project is licensed under the [MIT License](LICENSE).
```
