## **Key Features**

### **🔑 Customer’s Side**

#### **🔐 User Authentication**
- **Login:** Securely access your account using Google Email or Email and password-based authentication (Firebase SDK Authentication).
- **Register:** Create a new account using Password-Based Account (Firebase SDK Authentication).

#### **🚗 Car Search and View Available Cars**
- **Search Cars:** Easily find the perfect car based on your search for a car name and other available details.
- **Browse Information:** Explore detailed information about cars, including:
  - Brand
  - Model
  - Pricing
  - Availability
  - Location
  - Seats
  - Car description

#### Car Rental Process
- **Rent a Car:** Select your desired car for rental.
- **Set Dates:** Choose valid start and end dates for your rental period.

#### **💳 Payment Options**
- **Flexible Payment Methods:** Select your preferred payment option (e.g., card, Klarna).
- **Make Payments:** Complete your transaction and see the total fee.
  - **Payment Information Format:**
    - Choose the Visa card and enter a valid Card Number, e.g., `4242 4242 4242 4242`.
    - Enter the month and year in the future.
    - Enter the card CVC (three numbers).
    - Enter the Zip Code in the Canadian format (e.g., `H7Y8U9`).
    - Click on the "Pay" button.

#### **🗒 Post-Rental Management**
- **View Contracts:** Navigate to your rental contract(s) anytime after booking.

#### **👤 Account Management**
- **Account Details:** View your personal information, including name, Gmail, date of account creation, and set your avatar.
- **Logout:** Securely exit your account.

### Admin’s Side

#### **🔐 User Authentication**
- **Login:** Securely access your account using Google Email or Email and password-based authentication (Firebase SDK Authentication).

#### Car Management
- **Add New Cars:**
  - Enter details such as car model, brand, seating capacity, location, price, and upload photos (optional).
- **View All Cars:**
  - Browse the complete list of cars available in the system.
- **Edit Car Details:**
  - Update information like pricing, brand, model, availability, location, image, or car’s description.

#### **📄 Contract Oversight**
- **View Customer’s Contracts:**
  - Access and edit the status of rental contracts associated with user bookings (e.g., completed, canceled, active).

#### **🔒 Account Management**
- **Account Control Functions:**
  - View all users and block a user.
- **Logout:** Securely exit your account.

---

## **Technologies Used**

### Frontend
- **Android Studio Koala (2024.1.1 Patch 2):** IDE used for developing the Android App.
- **XML 1.0:** For designing the user interface (UI) components.
- **Java 8:** Processes the business logic and user interactions.
- **Gradle:** Build automation tool for managing dependencies.

### **🔧 Backend**
- **Authentication:** Integrating email/password-based Firebase SDK authentication and Google Sign-in for secure login.
- **Secure Session Management:** Firebase automatically manages session states, enabling customers to stay logged in across sessions without compromising security.
- **Firebase Storage:** Securely stores and manages high-resolution images of cars for efficient retrieval and scalability.

### **📊 APIs**
- **Google Login API:** Establishes user sign-in and account management.
- **Stripe API:** Secure online payment processing.
- **Google Location API:** Provides valid and dynamic location services, including the car’s pickup location.
- **Google Calendar API:** Integrates booking schedules and reminders into customers' Gmail calendars.

### **🛠️ Platforms**
- **Firebase Console:** For monitoring app performance, usage analytics, and push notifications.
- **GitHub:** Allows version control and updates, and collaboration.

### **📘 Testing**
- **Emulators:** Used Pixel 5 API 30 for app testing.

---

## **How to Use This Repository**
1. Clone the repository to your local machine using `git clone`.
2. Open the project in Android Studio Koala (2024.1.1 Patch 2).
3. Set up Firebase credentials and Stripe API keys in the respective files.
4. Run the app on an emulator or a connected device for testing.

---

## Final Note

📌 **Please check further info inside the PDF** ❗

**Enjoy using the Car Rental Management App and elevate your car rental experience!**

