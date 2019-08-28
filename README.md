# <p align="center">How to use this Basic Authentication API</p>

Base URL = `https://ilovelambda.herokuapp.com/`

## Endpoints

- POST `api/auth/register`
- POST `api/auth/login`

Both end points require an object with this shape/schema:

```
{
    "username": "username",
    "password": "123"
}
```

### Create a directory for your server to live
