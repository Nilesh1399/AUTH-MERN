# AUTH-MERN

Authentication Page
This page provides a secure authentication system using JSON Web Tokens (JWT) and bcrypt for password hashing.

Features
Signup: Create a new user account with a unique email and password.
Login: Log in to an existing user account using email and password.
Token-based Authentication: Upon successful login, a JWT token is generated and returned to the user. This token can be used to access protected routes.

Technical Details
Password Hashing: bcrypt is used to hash and store user passwords securely.
Token Generation: JWT tokens are generated using a secret key and are valid for a specified period.
Token Verification: Tokens are verified on each request to protected routes to ensure authenticity.

Security Notes
Passwords are hashed and stored securely using bcrypt.
JWT tokens are generated and verified using a secret key.
Tokens are valid for a specified period to prevent unauthorized access.
