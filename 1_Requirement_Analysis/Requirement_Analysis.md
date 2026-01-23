# Requirement Analysis – Service Marketplace Web Application

## Project Overview
This project demonstrates end-to-end manual testing of a Service Marketplace web application, 
similar to platforms like Urban Company. Users can book services, make payments, manage orders, 
and provide feedback. This analysis defines the functional and non-functional requirements for testing.

-----------------//-----------------------------------//--------------------------------------//----------- 

## Modules

1. User Registration & Login
2. Service Discovery
3. Service Booking
4. Payment (Mock)
5. Order Management
6. Ratings & Reviews
7. Notifications

-------------------------//-----------------------------------//-------------------------------------------//----

## 1. User Registration & Login

### Functional Requirements
- User can register using email and mobile number
- OTP verification is required for registration
- User can log in using valid credentials
- Forgot password feature should work
- Error message displayed for invalid login attempts

### Non-Functional Requirements
- Login response time should be under 3 seconds
- Passwords must be securely stored (mocked for this project)
- UI should be responsive for desktop and tablet

------------------------------//---------------------------------//--------------------------------------------//----

## 2. Service Discovery

### Functional Requirements
- Users can search services by category
- Users can filter by location, price, and rating
- Search results show service provider details
- User can view service details (description, price, duration)

### Non-Functional Requirements
- Search results should display within 2 seconds
- UI should handle up to 20 services per page

---------------------------------------//--------------------------------------//---------------------------------------

## 3. Service Booking

### Functional Requirements
- User can select service, date, and time slot
- Booking confirmation is displayed
- Booking should be saved under user's order history
- Error message shown if slot unavailable

### Non-Functional Requirements
- Booking page should load in less than 3 seconds
- No overlap should occur in double booking (mocked logic)

-------------------------------//----------------------------------------//---------------------------------------//-----

## 4. Payment (Mock)

### Functional Requirements
- User can choose between multiple payment options (Credit Card, UPI, Wallet)
- Payment confirmation message should be displayed
- Failed transactions should display error messages

### Non-Functional Requirements
- Payment simulation should respond within 5 seconds
- UI must mask sensitive data

-------------------------------------------//---------------------------------------------//---------------------------

## 5. Order Management

### Functional Requirements
- Users can view current and past orders
- Users can cancel an order before service starts
- Users can reschedule order
- Service providers can update order status

### Non-Functional Requirements
- Order list should load in under 2 seconds
- Must maintain consistent formatting for dates and status

------------------------//------------------------------------------------//----------------------------------//---------

## 6. Ratings & Reviews

### Functional Requirements
- User can give rating (1-5 stars) after service completion
- User can write feedback
- Ratings appear on service provider profile

### Non-Functional Requirements
- Feedback form must handle at least 200 characters
- Average rating should calculate correctly

---------------------------------//--------------------------------------------//----------------------------------------

## 7. Notifications

### Functional Requirements
- User receives booking confirmation notifications
- User receives cancellation notifications
- Reminder notifications before service

### Non-Functional Requirements
- Notifications should appear in <2 seconds
- Must be visually distinguishable (color/format) for desktop

----------------//--------------------------------------------//--------------------------------------//----------------

## Assumptions / Constraints
- Payment is simulated, no real transactions
- Service provider login is not part of this scope
- Web application tested on Chrome browser only
- Mobile responsiveness is checked in tablet resolution only

-------//-----------------------------------//--------------------------------------//------------------------

## References
- Urban Company web application for feature inspiration
