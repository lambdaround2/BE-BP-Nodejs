# <p align="center">How to use this Basic Authentication API</p>

Base URL = `https://ilovelambda.herokuapp.com/`

## Endpoints

- POST `/api/auth/register`
- POST `/api/auth/login`
- GET `/api/users` (return list of all users)
- GET `/api/users/:id` (returns a single user by id)

Both end points require an object with this shape/schema:

```
{
    "username": "username",
    "password": "123"
}
```
