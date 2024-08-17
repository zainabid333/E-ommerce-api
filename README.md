# E-Commerece API
An API that is used for Creating,retreiving,deleting and updating the products in there respective categories and link them to there tags

## Installation
- Setup your local envoirnment variables in .env file
- setup your database using psql server.
- Initate the project with the following command to install the necessary files:
    ```
        npm i
    ```
- seed the database using the following commands:
    ```
        npm run seed
    ```
- Run the application:

        npm start
- As this is a back-end API so it's only tested in Insomnia

# Technologies Used

- Node.js
- PostgreSQL
- Sequelize
- express.JS
## Usage

### Products
- Add a single product using JSON structure:
    ```
    {
        product_name: "Name for product",
        stock: 10,
        category_id: 1 
        tags: [1,2,3]
    }
- View all products.
- View a single product by it ID.
- Delete a product by it's ID.
-Update a product by the same method as adding a product and you and only enter what you want to update.

### Categories
- View all categories.
- View a single category and it's related products by it's ID.
- Create a new categor by providing a JSON category_name.
- Delete a categor by it's ID.
- Update a category by using category_name.

### Tags

- View all tags.
- View a tag by it's ID
- Delete a tag by it's ID.
- Update a tag by providing tag_name.
- Create a new tag by providing tag_name.

## Screenshots
![options for app running](./assets/images/options.png)
![viewing options](./assets/images/viewing%20optons.png)

## Contributions
Contributions are welcome. Please open an issue or submit a pull request for any improvements.

## License
[MIT License](LICENSE)

## Repository Link

[OrionHRIS](https://github.com/zainabid333/OrionHRIS)

## Walkthrough Video Link
[Walkthrough Vidio](https://drive.google.com/file/d/1CkX41KlNd0nYkdVmnH5twJLWBMq5fk5g/view)


