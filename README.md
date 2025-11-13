# SweetManager

**SweetManager** is a comprehensive hotel management software that streamlines operations for hotel owners and admins. The platform allows for easy management of room details, booking processes, staff communication, and inventory supplies. SweetManager not only supports internal hotel administration, but also offers guests access to all hotels listed on the platform, allowing them to filter options and enjoy a fast and simple booking process. 

Additionally, based on the guest’s preferences, the room will be set to a specific temperature. Upon arrival at the hotel, the guest will receive an RFID card for easy access to their room and public areas.

---

## Features

- **Role-Based Access**: Different functionalities for managers, workers, and main administrators.
- **Real-Time Notifications**: Admins can send notifications to specific worker areas in real time.
- **Room Management**: View and manage room details, bookings, and availability.
- **Supplies and Inventory**: Manage stock levels and ensure proper communication with suppliers.
- **Subscription Model**: Owners can subscribe to manage their hotel organization and invite their staff.
- **Income and Expense Management**: Owners can view analytics about recent income and expenses for their hotel.

---

## Roles

- **ROLE_OWNER**: Full administrative control, including subscription management and organization setup.
- **ROLE_ADMIN**: Manage hotel-wide operations, including rooms, bookings, and notifications.
- **ROLE_GUEST**: Search for hotels and enjoy an easy onboarding process. With a global profile, guests can set their preferred room temperature related to their bookings.

---

## Tech Stack

- **Frontend**: Vue (with Vite for bundling)
- **Backend**: .NET Web API
- **Database**: MySQL (with JWT Authentication for secure access)
- **Containerization**: Docker (for easy deployment with both API and MySQL containers)
- **Architecture**: CQRS, Domain-Driven Design, SCRUM for development process