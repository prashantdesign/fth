# Software Requirements Specification (SRS)

## 1. Introduction
From The Heart is a premium gifting platform that combines physical products, personalized websites, QR experiences, guest checkout, and admin-managed operations.

## 2. System Overview
The platform shall support:
- Product browsing and checkout
- Gift hamper orders
- Personalized website generation
- Dynamic QR cards
- Admin panel operations
- Reports and analytics
- Shipping and inventory control

## 3. Technology Stack
- Frontend: HTML, CSS, JavaScript
- Backend: PHP 8+
- Database: MySQL
- Hosting: Hostinger
- Compatibility: Mobile-first responsive design

## 4. Functional Requirements
### 4.1 Customer Experience
- Browse products by category and occasion
- Use guest checkout
- Place physical, digital, and combo orders
- Upload photos, videos, and messages
- Create or request personalized websites
- Track orders using email or mobile number

### 4.2 Website Builder
- Provide 4-5 initial themes
- Support DIY and managed creation modes
- Allow admin code editing per theme
- Generate QR-linked websites
- Support custom colors, music, password protection, and guest wishes

### 4.3 QR System
- Generate dynamic QR codes
- Allow QR destination updates
- Support analytics and downloads
- Support password-protected pages and expiry redirects

### 4.4 Order Management
- Support order status workflow
- Track product personalization and packaging
- Include handwritten notes and QR cards where applicable

### 4.5 Admin System
- Manage products, categories, inventory, coupons, shipping, and orders
- View analytics, reports, and activity logs
- Configure global and product-level shipping
- Manage COD rules by location

## 5. Non-Functional Requirements
- Fast page loading
- SEO-friendly structure
- Secure user data handling
- Scalable architecture
- Maintainable codebase
- Browser compatibility on modern browsers
- Mobile responsiveness

## 6. Security Requirements
- OTP verification for order lookup
- Secure password hashing
- CSRF protection
- XSS protection
- SQL injection protection
- File upload validation

## 7. Acceptance Criteria
The system is acceptable when:
- Customers can complete purchases successfully
- Personalized websites can be created and accessed via QR
- Admin can manage all core business flows from the dashboard
- Shipping, coupons, and inventory rules work as configured