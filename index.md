
# Design Rest API
1. User
-  Create User
   - Method = POST
   - Endpoint = api/v1/user
   - Header:
   - Content-Type : aplication/json
   - Auth : Bearer Token
   - Body
      ```
      {
          "id":2,
          "username":"USERNAME",
          "Created_At":"BySystem",
          "Updated_At":"BySystem",
          "phone":"",
          "address":" "
      }

    - Response:
      ```
      {
          "code": (respon code),
          "message":"Successfully created"
      }

- Read User
  - Method GET
  - Endpoint = api/v1/user/read
  - Header:
  - Content-Type : aplication/json
  - Auth : Bearer Token
  - Body
    ```
    {
        "id":2,
        "username":"username",
        "phone":"number",
        "address":"address"
    }

  - Response:
    ```
    {
        "code": (respon code),
        "message":"Successfully created"
    }

- Update User
  - Method PUT
  - Endpoint = api/v1/user=id
  - Header:
  - Content-Type : aplication/json
  - Auth : Bearer Token
  - Body
    {

    }

  - Response:
    ```
    {
        "code": (respon code),
        "message":"Successfully updated"
    }
    
- Delete User
  - Method DELETE
  - Endpoint = api/v1/user=id
  - Header:
  - Content-Type : aplication/json
  - Auth : Bearer Token
  - Response:
    ```
    {
        "code": (respon code),
        "message":"Successfully delete"
    }

2. Produk

3. Brand


```
- Kebutuhan Pengembangan
- Java version : Latest,




