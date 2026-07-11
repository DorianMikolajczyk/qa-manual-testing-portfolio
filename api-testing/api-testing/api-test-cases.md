
Test Case ID:
TC-API-001

Title:
Get user details using API

Method:
GET

Endpoint:
https://jsonplaceholder.typicode.com/users/1

Steps:
1. Open Postman.
2. Select GET method.
3. Enter API endpoint.
4. Click Send.

Expected Result:
- Response status code is 200 OK.
- Response contains user data.
- Response contains fields:
  id, name, username, email.


  Test Case ID:
TC-API-002

Title:
Create new user using API

Method:
POST

Endpoint:
https://jsonplaceholder.typicode.com/users

Request Body:

{
  "name": "John Tester",
  "email": "john@test.com"
}

Steps:
1. Select POST method.
2. Add JSON body.
3. Click Send.

Expected Result:
- Response status code is 201 Created.
- API returns created user data.

Test Case ID:
TC-API-003

Title:
Update existing user

Method:
PUT

Endpoint:
https://jsonplaceholder.typicode.com/users/1

Steps:
1. Select PUT method.
2. Add updated JSON data.
3. Click Send.

Expected Result:
- Response status code is 200 OK.
- Updated data is returned in response.

Test Case ID:
TC-API-004

Title:
Delete user

Method:
DELETE

Endpoint:
https://jsonplaceholder.typicode.com/users/1

Steps:
1. Select DELETE method.
2. Click Send.

Expected Result:
- Response status code is 200 OK or 204 No Content.
- User should be removed.

Test Case ID:
TC-API-005

Title:
Get user with invalid ID

Method:
GET

Endpoint:
https://jsonplaceholder.typicode.com/users/9999

Steps:
1. Send GET request with non-existing user ID.

Expected Result:
- API returns 404 Not Found.
- Error response is displayed.

