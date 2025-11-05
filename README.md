# 🍔 E-Food Shop — JavaFX Project

A full-featured **Food Delivery and Restaurant Management System** built using **JavaFX**, **MySQL**, and **FXML**.  
It includes dashboards for **Customers**, **Restaurants**, and **Deliverymen**, as well as AI assistance, live delivery tracking, and an integrated feed system.

---

## 🚀 Features

### 👨‍💻 User Features
- Register / Login securely
- Browse restaurant posts & menus  
- Add food items to cart  
- Place and track orders  
- View order history and reviews  
- Chat with restaurants or AI assistant

### 🍕 Restaurant Dashboard
- Manage menu & product posts  
- Handle customer orders  
- View and respond to reviews  
- Track earnings  
- AI assistant for automatic customer replies  

### 🛵 Deliveryman Dashboard
- View assigned orders  
- Real-time map tracking (Leaflet + OpenStreetMap)  
- Update order status (`Picked`, `On The Way`, `Delivered`)  
- View total earnings and completed deliveries  

### 🤖 AI Assistant
- Built-in chatbot for quick help  
- Uses `ai_chat_history` and `ai_responses` tables  
- Context-aware responses stored in the database  

---

## 🗺️ Technologies Used

| Technology | Purpose |
|-------------|----------|
| **JavaFX** | Frontend UI framework |
| **FXML** | Layouts for UI design |
| **CSS** | Styling for scenes |
| **MySQL** | Database for all system data |
| **Leaflet.js (via WebView)** | Map integration for live tracking |
| **Jakarta Mail** | Email verification & notifications |

---

## 🧩 Database Structure

**Database Name:** `sample`

Contains tables for:
- `user_information`
- `resturent_info`
- `deliveryman_info`
- `orders`
- `deliveryman_location`
- `buy_history`
- `review_post`
- `posts`
- `ai_chat_history`
- `ai_responses`
- `earnings`
- `notifications`

📦 You can import the full SQL schema:
[`sample_full_project_final.sql`](./sample_full_project_final.sql)

---

## 🛠️ Setup Instructions

1. **Install Requirements**
   - Java JDK 17+  
   - JavaFX SDK 21  
   - MySQL Server  
   - Git (optional)

2. **Create Database**
   - Open phpMyAdmin  
   - Create a new database named `sample`  
   - Import the file: `sample_full_project_final.sql`

3. **Configure Database in Code**
   In `DataBase.java`:
   ```java
   private static final String DATABASE_URL = "jdbc:mysql://localhost:3306/sample";
   private static final String DATABASE_USERNAME = "root";
   private static final String DATABASE_PASSWORD = "";
   ```

4. **Run the Application**
   - Open your terminal in the project folder  
   - Run:
     ```bash
     java --module-path "C:\javafx-sdk-21.0.1\lib" --add-modules javafx.controls,javafx.fxml -jar target/E_Shop.jar
     ```

---

## 📷 Screenshots (Add Later)
- 🏠 Login Page  
- 🍽️ Restaurant Dashboard  
- 🛵 Delivery Map  
- 💬 AI Chat Assistant  

*(You can add screenshots here once you upload images to your GitHub repo.)*

---

## 💡 Future Improvements
- Admin dashboard for system-wide management  
- Payment gateway integration  
- Push notifications for delivery updates  
- Multi-language support  

---

## 👨‍💻 Author

**Ifteir Hossain**  
📧 ifteirhossain445@gmail.com  
🔗 [GitHub Profile](https://github.com/ifteir)
