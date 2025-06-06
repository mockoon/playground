<div align="center">
  <a href="https://mockoon.com" alt="mockoon logo">
    <img width="200" height="200" src="https://mockoon.com/images/logo-square-playground.png">
  </a>
  <br>
  <a href="https://mockoon.com/"><img src="https://img.shields.io/badge/Website-Go-green.svg?style=flat-square&colorB=1997c6"/></a>
  <a href="https://mockoon.com/newsletter/"><img src="https://img.shields.io/badge/Newsletter-Subscribe-green.svg?style=flat-square"/></a>
  <br>
  <br>
  <h1>Mockoon's Playground</h1>
</div>

Mockoon's playground is a ready-to-use mock API for all your prototyping needs: fake JSON data, JSON placeholders, realistic CRUD API mock, etc. It is also a good way to discover Mockoon's features.

➡️ Playground API URL: [https://playground.mockoon.com](https://playground.mockoon.com)
➡️ [Playground's documentation](https://mockoon.com/playground/)

The playground offers the following resources, populated with fake data (generated using [Faker.js](https://fakerjs.dev/)):

- [`/companies`](https://playground.mockoon.com/companies): a CRUD endpoint with fake companies.
- [`/contacts`](https://playground.mockoon.com/contacts): a CRUD endpoint with fake contacts.
- [`/customers`](https://playground.mockoon.com/customers): a CRUD endpoint with fake customers.
- [`/movies`](https://playground.mockoon.com/movies): a CRUD endpoint with fake movies.
- [`/notifications`](https://playground.mockoon.com/notifications): a CRUD endpoint with fake notifications.
- [`/photos`](https://playground.mockoon.com/photos): a CRUD endpoint with fake photos.
- [`/pokemons`](https://playground.mockoon.com/pokemons): a CRUD endpoint with fake pokemons (read-only).
- [`/posts`](https://playground.mockoon.com/posts): a CRUD endpoint with fake posts.
- [`/sales`](https://playground.mockoon.com/sales): a CRUD endpoint with fake sales.
- [`/todos`](https://playground.mockoon.com/todos): a CRUD endpoint with fake todos.
- [`/users`](https://playground.mockoon.com/users): a CRUD endpoint with fake users.

The following routes are available for each resource (replace `{resources}` with the resource name, e.g. `companies`):

- `GET /{resources}`: Returns the entire array.
- `GET /{resources}/:id`: Returns an object by its id property.
- `POST /{resources}`: Inserts a new object in the array (autogenerate the id (UUID) if not provided).
- `PUT /{resources}/:id`: Performs a full object update by its id (replace).
- `PATCH /{resources}/:id`: Performs a partial object update by its id (merge).
- `DELETE /{resources}/:id`: Deletes an object by its id.

You can also use the sorting, searching and filtering query parameters on the main GET route, example: `?property_eq=test&page=2&limit=50`. You will find more information about the CRUD routes behavior in our [documentation](https://mockoon.com/docs/latest/api-endpoints/crud-routes/).

> 💡 The following routes are disabled: `DELETE /{resources}`, `PATCH /{resources}`, `PUT /{resources}`. POST, DELETE, PATCH and PUT requests are persisted. GET requests are cached.

> ⚠️ The playground is a shared resource (please don't abuse it) and is not meant to be used in production. Data are frequently reset.

To go further, download Mockoon and discover all its [features](https://mockoon.com/features/).

➡️ [Download Mockoon](https://mockoon.com/download/)

## Support/feedback

You can discuss all things related to Mockoon, and ask for help, on the [official community](https://github.com/mockoon/mockoon/discussions). It's also a good place to discuss bugs and feature requests before opening an issue on this repository.

## Contributing

If you are interested in contributing to Mockoon, please take a look at the [contributing guidelines](https://github.com/mockoon/mockoon/blob/main/CONTRIBUTING.md).

Please also take a look at our [Code of Conduct](https://github.com/mockoon/mockoon/blob/main/CODE_OF_CONDUCT.md).

## Roadmap

If you want to know what will be coming in the next release you can check the global [Roadmap](https://mockoon.com/public-roadmap/) or [subscribe to our newsletter](https://mockoon.com/newsletter/).
