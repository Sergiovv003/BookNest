# API Endpoints

## POST /api/signup
Create a new user.

### Request
```
{ "email": "test@example.com", "password": "secret" }
```

## POST /api/login
Returns a JWT token.

### Request
```
{ "email": "test@example.com", "password": "secret" }
```

## GET /api/profile
Return the logged in user's profile. Requires `Authorization: Bearer <token>` header.
