# Smash Zone API

## REST API Specification

- Local: <http://localhost:3000>

| Endpoint        | HTTP     | Description              | Implemented |
| --------------- | -------- | ------------------------ | ----------- |
| `/products`     | `GET`    | Get all products         | ✅          |
| `/products/:id` | `GET`    | Get one product by id    | ✅          |
| `/products`     | `POST`   | Add new product          | ✅          |
| `/products`     | `DELETE` | Delete all products      | ✅          |
| `/products/:id` | `DELETE` | Delete one product by id | ✅          |
| `/products/:id` | `PUT`    | Update one product by id | ✅          |

To install dependencies:

```sh
bun install
```

To run:

```sh
bun run dev
```
