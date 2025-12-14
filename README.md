# 👗 Jama Lagbe? - Sustainable Fashion Marketplace

![Java](https://img.shields.io/badge/Language-Java-orange?style=for-the-badge&logo=java) ![Platform](https://img.shields.io/badge/Platform-Android-green?style=for-the-badge&logo=android) ![Database](https://img.shields.io/badge/Database-MySQL-blue?style=for-the-badge&logo=mysql)

**"Jama Lagbe?"** (Do you need clothes?) is an Android-based e-commerce platform designed to promote sustainable fashion in Bangladesh. It bridges the economic gap between high-end fashion consumers and budget-conscious users by enabling a circular economy of **Buying, Selling, and Renting**.

---

## 🌏 The Mission

In developing nations like Bangladesh, there is a distinct economic divide:
1.  **The Accumulators:** People who buy expensive, high-quality fashion but only wear it for 2-3 months before it sits idle.
2.  **The Aspirants:** People who need quality attire for short-term events (weddings, interviews) or daily use but cannot afford high retail prices.

**The Solution:**
This platform connects these two groups. By allowing users to **Rent** expensive items for short periods or **Buy** used quality items at lower prices, we reduce textile waste and make fashion accessible to everyone.

---

## 🚀 Key Features

### 🛒 Marketplace Ecosystem
* **Buy & Sell:** Users can list pre-loved or new clothing items with images and descriptions.
* **Rental System:** A unique feature allowing users to rent premium dresses (e.g., Sherwanis, Lehengas, Suits) for a fraction of the retail price.
* **Condition Grading:** Items are categorized as New, Like New, or Used.

### 👤 User Experience
* **User Profiles:** Separate dashboards for Buyers and Sellers.
* **Search & Filter:** Filter clothes by Category (Men, Women, Kids), Price, and Rental availability.
* **Secure History:** Complete transaction logs and rental history tracking.

---

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Language** | Java (Android SDK) |
| **IDE** | Android Studio |
| **UI Design** | XML (Material Design Components) |
| **Database** | MySQL (Relational Data Management) |
| **Connectivity** | JDBC / PHP Middleware (Depending on your implementation) |


---

## 🔧 Installation & Setup

To run this project locally, you need Android Studio and a local MySQL server (like XAMPP).

1.  **Clone the Repo**
    ```bash
    git clone [https://github.com/Mazharul-Khan/Jama_Lagbe_Android_App.git](https://github.com/Mazharul-Khan/Jama_Lagbe_Android_App.git)
    ```

2.  **Database Setup**
    * Install XAMPP or WAMP.
    * Start **Apache** and **MySQL**.
    * Go to `localhost/phpmyadmin`.
    * Create a database named `jama_lagbe_db`.
    * Import the `database_schema.sql` file provided in this repository.

3.  **Android Studio**
    * Open the project in Android Studio.
    * Navigate to the Database Configuration file (usually in `utils/DatabaseHelper.java`).
    * Ensure the IP address matches your local machine's IP (e.g., `192.168.x.x`) to connect the Emulator to your local MySQL server.
    * Build and Run on an Emulator or Physical Device.

---

## 🔮 Future Improvements

* **Integrated Payment Gateway:** Adding bKash/Nagad integration for seamless payments.
* **AI Recommendation:** Suggesting clothes based on user size and preference.
* **In-App Chat:** Real-time negotiation between buyers and sellers.
* **Logistics Integration:** Partnering with courier services for pickup and delivery.

---


**Developed by Md Mazharul Islam Khan**
