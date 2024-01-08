<div align="center">
  <a href="https://mockoon.com" alt="mockoon logo">
    <img width="200" height="200" src="https://mockoon.com/images/logo-square-playground.png">
  </a>
  <br>
  <a href="https://mockoon.com/"><img src="https://img.shields.io/badge/Website-Go-green.svg?style=flat-square&colorB=1997c6"/></a>
  <a href="https://mockoon.com/newsletter/"><img src="https://img.shields.io/badge/Newsletter-Subscribe-green.svg?style=flat-square"/></a>
  <a href="https://twitter.com/GetMockoon"><img src="https://img.shields.io/badge/Twitter_@GetMockoon-follow-blue.svg?style=flat-square&colorB=1da1f2"/></a>
  <a href="https://discord.gg/FtJjkejKGp"><img src="https://img.shields.io/badge/Discord-go-blue.svg?style=flat-square&colorA=6c84d9&colorB=1da1f2"/></a>
  <br>
  <br>
  <h1>Mockoon's Playground</h1>
</div>

Mockoon's playground is a ready-to-use mock API for all your prototyping needs: fake JSON data, JSON placeholders, realistic CRUD API mock, etc. It is also a good way to discover Mockoon's features.

➡️ Playground API URL: [https://playground.mockoon.com](https://playground.mockoon.com)
➡️ [Playground's documentation](https://mockoon.com/playground/)

The playground offers the following resources, populated with fake data (generated using [Faker.js](https://fakerjs.dev/)):

- [`/contacts`](https://playground.mockoon.com/contacts): a CRUD endpoint with fake contacts.
- [`/movies`](https://playground.mockoon.com/movies): a CRUD endpoint with fake movies.
- [`/photos`](https://playground.mockoon.com/photos): a CRUD endpoint with fake photos.
- [`/posts`](https://playground.mockoon.com/posts): a CRUD endpoint with fake posts.
- [`/todos`](https://playground.mockoon.com/todos): a CRUD endpoint with fake todos.
- [`/users`](https://playground.mockoon.com/users): a CRUD endpoint with fake users.

The following routes are available for each resource:

- `GET /resources`: Returns the entire array.
- `GET /resources/:id`: Returns an object by its id property.
- `POST /resources`: Inserts a new object in the array (autogenerate the id (UUID) if not provided).
- `PUT /resources/:id`: Performs a full object update by its id (replace).
- `PATCH /resources/:id`: Performs a partial object update by its id (merge).
- `DELETE /resources/:id`: Deletes an object by its id.

You can also use the sorting, searching and filtering query parameters on the main GET route, example: `?property_eq=test&page=2&limit=50`. You will find more information about the CRUD routes behavior in our [documentation](https://mockoon.com/docs/latest/api-endpoints/crud-routes/).

> 💡 The following routes are disabled: `DELETE /resources`, `PATCH /resources`, `PUT /resources`. POST, DELETE, PATCH and PUT requests are persisted. GET requests are cached.

> ⚠️ The playground is a shared resource (please don't abuse it) and is not meant to be used in production. Data are frequently reset.

To go further, download Mockoon and discover all its [features](https://mockoon.com/features/).

➡️ [Download Mockoon](https://mockoon.com/download/)

## Support/feedback

You can discuss all things related to Mockoon, and ask for help, on the [official community](https://github.com/mockoon/mockoon/discussions). It's also a good place to discuss bugs and feature requests before opening an issue on this repository. For more chat-like discussions, you can also join our [Discord server](https://discord.gg/FtJjkejKGp).

## Contributing

If you are interested in contributing to Mockoon, please take a look at the [contributing guidelines](https://github.com/mockoon/mockoon/blob/main/CONTRIBUTING.md).

Please also take a look at our [Code of Conduct](https://github.com/mockoon/mockoon/blob/main/CODE_OF_CONDUCT.md).

## Roadmap

If you want to know what will be coming in the next release you can check the global [Roadmap](https://mockoon.com/public-roadmap/).

New releases will be announced on Mockoon's [Twitter account @GetMockoon](https://twitter.com/GetMockoon) and through the newsletter to which you can subscribe [here](https://mockoon.com/newsletter/).
