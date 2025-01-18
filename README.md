# API Endpoints

Welcome to the Restaurant API! Below is the list of available endpoints and their functionalities:

## Endpoints

### Restaurant
- **`/restaurant/`**  
  Access general restaurant-related information.

### Booking
- **`/restaurant/booking/`**  
  Manage restaurant bookings.  
- **`/restaurant/booking/tables/`**  
  View or manage table availability and reservations.

### Menu
- **`/restaurant/menu/`**  
  Access the restaurant's menu details.

### Authentication
- **`/auth/users/`**  
  Create a new user account.  
- **`/auth/token/login/`**  
  Log in to obtain an authentication token.

## Authentication Token Usage

After successfully logging in via **`/auth/token/login/`**, a token will be generated.  
Include this token in your requests to authenticate API calls, such as:

- **`/restaurant/api-token-auth/`**  
  Authenticate using the token to access secured endpoints.
