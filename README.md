## 🔐 Security & Core Features

### Authentication & Authorization
- Secure user **registration, login, and logout** using Spring Security.
- **Role-based access control** with restricted endpoints for privileged (VIP) users.
- Password encryption using **BCrypt hashing**.

### Session & Request Security
- Secure handling of **browser refresh and session persistence**.
- Protection against unauthorized access using **JWT-based authentication**.
- Configured security filters to validate every incoming request.

### Order History – Core Functionality
- Users can view their **order history** with detailed order information.
- Orders are securely mapped to authenticated users only.

### Order History – Backend Security
- REST APIs protected using **Spring Security** and role-based access.
- Server-side validation to prevent unauthorized data access or manipulation.

### Order History – Frontend Security
- Access to order history restricted based on authentication state.
- Secure API integration ensuring only authorized users can fetch order data.

### Additional Security Measures
- Input validation and exception handling to prevent common vulnerabilities.
- Secure configuration of CORS and CSRF where applicable.
- Separation of concerns following clean architecture principles.
