# Task

- Create a NodeJS Server with following features.

# Getting Started

1. Create a folder `eval` inside
2. install required libraries.
3. `npm run start` command should start the Node Server on Port: `8000`

## Mandatory:

1. Use of ExpressJS.
2. Use go nodemon.
3. server should run on port: `8000`.
4. Command: `npm run start` should start the server.

## Schema

- [Users](./data/users.json) : check `data/users.json` file.
- [Products](./data/products.json.json) : check `data/products.json` file.

## Features to build

1. Create CRUD api's for `/users`
   - `GET /users`: get list of users
   - `GET /users/:id` : get one user where id matches.
   - `DELETE /users/:id` : delete one user where id matches.
   - `POST /users` : add one user where with dynamic id.
2. Create CRUD api's for `/products`.

   - `GET /products`: get list of products

     - `GET /products?tags=black` : get products where tags has `black`.
     - `GET /products?sizes=lg` : get products where size `lg` is applicable.
     - `GET /products?tags=black&sizes=lg` : get products where tags has `black` and where size `lg` is applicable.

     **Note** - Query filters applicable for `tags`, `size` and `colors`.

   - `GET /products/:id` : get one product where id matches.
   - `DELETE /products/:id` : delete one product where id matches.
   - `POST /products` : add one product where with dynamic id.

**Note** - `Make sure you implelement features one by one and deploy the app correctly`

## General Instructions (**_IMPORTANT_**)

1. Typescript is mandatory.
2. Use of Custom Hooks is mandatory
3. Do not use Global CSS, instead use `<componentName>.module.css` convention for Css in that file.
4. Do Not Remove `data-testid="xxxx"` from anywhere, this are used by testing tools to test your code, removal of this will lead to low score.
5. Make sure you use only the given components and dont create new files and folders as chaging component name, structures might result in giving you zero marks
6. Make sure you use only the given data and dont create new data, as chaging data might result in giving you zero marks

## Just for fun, things you can try (**_OPTIONAL_**)

- Try running `npm run test`
  - might help you to avoid obvious mistakes.
