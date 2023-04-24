1. Signup API
   http://localhost:8000/api/signup (POST)

Input:
{
"firstName": "Adithya",
"lastName": "B A",
"email": "adithyaba93@gmail.com",
"password": "Aganagan@4"
}

2. Signin API
   http://localhost:8000/api/signin (POST API)
   Input
   {
   "email": "adithyaba93@gmail.com",
   "password": "Aganagan@4"
   }

3.Signout API
http://localhost:8000/api/signout (GET API)

4. Testroute to test expressJwt
   http://localhost:8000/api/testroute (GET API)

5. Get all users
   http://localhost:8000/api/users (GET API)

6. Get single user
   http://localhost:8000/api/user/64464fc8f182684f749b7380 (GET API)

7. Update single user
   http://localhost:8000/api/user/64464fc8f182684f749b7380
   Input:
   {
   "firstName": "jhon"
   }

8. Create category
   http://localhost:8000/api/category/create/64464fc8f182684f749b7380 (POST Request)
   Input:
   {
   "name": "Winter"
   }

9. Get all categories
   http://localhost:8000/api/categories (GET Request)

10. Update category
    http://localhost:8000/api/category/642bd9f2226a51506099b593/64464fc8f182684f749b7380 (Update Request)
    Input:
    {
    "name": "Rainy"
    }

11. Delete Category
    http://localhost:8000/api/category/642bd9f2226a51506099b593/64464fc8f182684f749b7380 (DELETE Request)

12. Create Product
    http://localhost:8000/api/product/create/64464fc8f182684f749b7380 (POST Request)
    Input:
    Insert the data in form format.

13. Update Product
    http://localhost:8000/api/product/create/64464fc8f182684f749b7380 (PUT Request)
    Input:
    {
    "price: 1000
    }

14. Get all products
    http://localhost:8000/api/products (GET Request)

15. Delete Product
    http://localhost:8000/api/category/create/64464fc8f182684f749b7380 (DELETE Request)

16.
