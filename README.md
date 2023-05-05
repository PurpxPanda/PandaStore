# E-commerce Site Back End

This is the back end for an e-commerce site built using Express.js and Sequelize to interact with a MySQL database.

## Getting Started

To get started with the project, please follow the below steps:

1. Clone the repository on your local machine
2. Navigate to the project directory
3. Run `npm install` to install all the required dependencies
4. Create a `.env` file based on the `.env.EXAMPLE` file and fill in the required values
5. Run `npm run seed` to seed the database with some initial data
6. Run `npm start` to start the server
7. Use a tool like insomnia to interact with endpoints.

## API Endpoints

The following endpoints are available:

### Products

- `GET /api/products` - returns a list of all products
- `GET /api/products/:id` - returns a single product with the specified id
- `POST /api/products` - creates a new product
- `PUT /api/products/:id` - updates an existing product with the specified id
- `DELETE /api/products/:id` - deletes a product with the specified id

### Categories

- `GET /api/categories` - returns a list of all categories
- `GET /api/categories/:id` - returns a single category with the specified id
- `POST /api/categories` - creates a new category
- `PUT /api/categories/:id` - updates an existing category with the specified id
- `DELETE /api/categories/:id` - deletes a category with the specified id

### Tags

- `GET /api/tags` - returns a list of all tags
- `GET /api/tags/:id` - returns a single tag with the specified id
- `POST /api/tags` - creates a new tag
- `PUT /api/tags/:id` - updates an existing tag with the specified id
- `DELETE /api/tags/:id` - deletes a tag with the specified id

## Dependencies

This project uses the following dependencies:

- express
- mysql2
- sequelize
- dotenv

## Contributing

Contributions are welcome. Please create a pull request with any changes or additions.

## License

This project is licensed under the MIT License.
