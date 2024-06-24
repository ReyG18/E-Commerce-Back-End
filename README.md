# E-Commerce Back End

This project is the back end for an e-commerce site. It provides a RESTful API built with Express.js, Sequelize, and PostgreSQL. The API allows for managing products, categories, and tags, including creating, reading, updating, and deleting these entities.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Walkthrough Video](#walkthrough-video)
- [Questions](#questions)

## Installation

To get a local copy up and running, follow these simple steps:

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Clone the Repository

```bash
git clone <repository_url>
cd e-commerce-back-end
```

### Install Dependencies

```bash
npm install
```

### Set Up Environment Variables

Use the included .env.EXAMPLE to create your own env using your own credentials.

```bash
DB_NAME='ecommerce_db'
DB_USER='your_postgres_username'
DB_PASSWORD='your_postgres_password'
```

### Seed the Database

```bash
npm run seed
```

### Start the Server

```bash
npm start
```

## Usage

- Use Insomnia to test the API endpoints.
- The base URL for the API is <http://localhost:3001/api>.

### Endpoints

#### Products

- GET /products - Get all products
- GET /products/:product_id - Get a product by ID
- POST /products - Create a new product
- PUT /products/:product_id - Update a product by ID
- DELETE /products/:product_id - Delete a product by ID

#### Categories

- GET /categories - Get all categories
- GET /categories/:category_id - Get a category by ID
- POST /categories - Create a new category
- PUT /categories/:category_id - Update a category by ID
- DELETE /categories/:category_id - Delete a category by ID

#### Tags

- GET /tags - Get all tags
- GET /tags/:tag_id - Get a tag by ID
- POST /tags - Create a new tag
- PUT /tags/:tag_id - Update a tag by ID
- DELETE /tags/:tag_id - Delete a tag by ID

## Walkthrough Video

[Click me]()

## Questions

For questions about the project, please contact @ReyG18 or <garibay_r18@yahoo.com>.
