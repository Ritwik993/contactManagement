# Contact Management System

## Overview
The **Contact Management System** is a tool designed to help users maintain and organize important contact information for customers and clients. It provides a centralized space where users can easily add, view, update, and delete contact details, making it an essential feature for businesses to manage client relationships efficiently. This streamlined access to contact information supports better communication and relationship-building efforts.

## Features
1. **Adding a New Contact**:
   - Users can add new contacts with essential details such as:
     - Name
     - Email
     - Phone Number
     - Company
     - Job Title
   - This functionality helps users expand their contact database and manage new clients/customers effectively.

2. **Viewing Contacts**:
   - A table view lists all contacts in an organized manner.
   - Features like sorting and pagination improve the user experience, making it easy to browse large contact lists and quickly find specific contacts.

3. **Editing Contact Information**:
   - Users can update existing contact information when details change (e.g., phone number, company, job title).
   - This ensures that the contact information remains current and reliable for effective communication.

4. **Deleting a Contact**:
   - Users can delete outdated or duplicate contacts, ensuring the contact list stays clean and relevant.
   - This helps maintain an up-to-date and efficient contact management system.

## Use Cases
- **Adding a New Contact**: Users can quickly add a contact by entering the necessary details in a form. This is useful for onboarding new clients or when new leads are acquired.
- **Viewing Contacts**: The system displays a comprehensive list of all saved contacts in a table format. Sorting and pagination features make navigation through extensive contact lists easy and efficient.
- **Editing Contact Information**: Users can select a contact and update any details that have changed, such as a phone number, company name, or job title.
- **Deleting a Contact**: Users can remove contacts that are no longer relevant, such as old client information or duplicates, helping to keep the database organized.

## Benefits
- **Time-saving**: A centralized location for all contact information ensures users can quickly access and manage contacts without searching through multiple systems or documents.
- **Efficiency**: The ability to add, view, update, and delete contacts in one place improves productivity and helps maintain accurate records.
- **Relationship Management**: Up-to-date contact details enhance communication, contributing to better client relationships and business success.

- ![image](https://github.com/user-attachments/assets/6719385e-ed77-4ce6-8270-85bd974a484c)


## Getting Started
### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/contact-management-system.git
2. Navigate to the project directory
3.   ```bash
     cd contact-management-system
4.  Install dependencies
    ```bash
     npm install
5.  Navigate to Frontend
      ```bash
     npm install
6.   Navigate to backend
       ```bash
     npm install

       
7.  Environment Variables Configuration

To run this project, you will need to create a `.env` file in the root directory and configure the following environment variables:

```bash
PORT=7777           # The port number on which the server will run
DB_URL=             # The database connection URL (e.g., MongoDB URI)
cloud_name=         # Cloudinary cloud name for image storage
api_key=            # Cloudinary API key
api_secret=         # Cloudinary API secret
JWT_SECRET=         # Secret key for signing JSON Web Tokens
JWT_EXPIRY=         # Expiry duration for JWT (e.g., 1d, 2h)
COOKIE_TIME=        # Expiry time for cookies (e.g., 7d)
