# Alterra_Kelompok2

Design Rest API
1.  User
   a. Create User
•	Method POST
•	Endpoint = api/v1/user
•	Header:
  o	Content-Type : aplication/json
  o	Auth : Bearer Token
•	Body
{
    "id":2,
    "username":"USERNAME",
    "Created_At":"BySystem",
    "Updated_At":"BySystem",
    "phone":"081234567890",
    "address":"menteng atas"
}

•	Response:
{
    "code": (respon code),
    "message":"Successfully created"
}

   b. Read User
•	Method GET
•	Endpoint = api/v1/user/read
•	Header:
  o	Content-Type : aplication/json
  o	Auth : Bearer Token
•	Body
{
    "id":2,
    "username":"username",
    "phone":"081234567890",
    "address":"menteng atas"
}

•	Response:
{
    "code": (respon code),
    "message":"Successfully created"
}

   c. Update User
•	Method PUT
•	Endpoint = api/v1/user=id
•	Header:
  o	Content-Type : aplication/json
  o	Auth : Bearer Token
•	Body
{
    
}

•	Response:
{
    "code": (respon code),
    "message":"Successfully updated"
}


   d. Delete User
•	Method DELETE
•	Endpoint = api/v1/user=id
  o	Content-Type : aplication/json
  o	Auth : Bearer Token

•	Response:
{
    "code": (respon code),
    "message":"Successfully delete"
}

2.  Produk

3. Brand
