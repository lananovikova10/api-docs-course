# Getting Started

## Prerequisites
- Necessary tools and software
    - HTTP client (e.g., Postman, curl)
    - API key

## Setting Up Your Environment
- Configuring the base URL
- Adding the API key to your requests

## Making Your First Request
- Example of a basic API request to retrieve all users

    ```bash
    curl -X GET "http://158.160.86.46/api/prod/users" -H "Authorization: Token YOUR_API_KEY"
  - ```
## Understanding the Response Format:

Example response for successful request:

```
[
    {
        "id": 123,
        "username": "newUser",
        "email": "user@example.com",
        "firstName": "Имя",
        "lastName": "Фамилия",
        "city": "Город",
        "age": 30
    },
    {
        "id": 124,
        "username": "anotherUser",
        "email": "anotheruser@example.com",
        "firstName": "Another",
        "lastName": "User",
        "city": "City",
        "age": 25
    },
    ...
]
```

### Explanation of response structure and data fields

## Error Handling

### Common error responses and how to handle them
- Error code 400: Bad Request
- Error code 401: Unauthorized
- Error code 404: User Not Found
- Error code 405: Method Not Allowed
- Error code 422: Unprocessable Entity
- Error code 500: Server Error

