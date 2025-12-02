# 📱 PocketAdmin (Student Management System)

> **A Python-based CLI application for managing academic records and visualizing class data.**
> *Originally coded entirely on a mobile phone.*

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange?style=for-the-badge&logo=mysql)
![Matplotlib](https://img.shields.io/badge/Data_Viz-Matplotlib-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Mobile%20%7C%20Desktop-lightgrey?style=for-the-badge)

## 📖 The Story: Engineering on a 6-Inch Screen
**PocketAdmin** is not just a database project; it is a proof of concept for mobile development.

Back in Class 12, I needed to build a final practical project but did not have access to a laptop. Instead of giving up, I utilized **Cloud IDEs (Replit & Google Colab)** to develop this entire application on my smartphone.

Every line of code, every SQL query, and every debugging session happened on a touch keyboard. This project represents my belief that **resourcefulness > resources**.

## ✨ Features
This system goes beyond basic CRUD operations by integrating data visualization:

* **📝 Record Management:** Add, Update, Delete, and View student records (Admission No., Roll No., Name, Class, etc.).
* **🔍 Search Functionality:** Rapidly find specific student details by Roll Number.
* **📊 Graphical Analysis:** Visualizes student distribution per class using **Matplotlib** (Bar Graphs).
* **🗄️ Automated Database Setup:** Automatically creates the `school_db` database and tables if they don't exist.

## 🛠️ Tech Stack
* **Language:** Python 3.8+
* **Database:** MySQL
* **Libraries:**
    * `mysql-connector-python` (Database Connectivity)
    * `matplotlib` (Data Visualization)
* **Development Environment:** Replit (Mobile), Google Colab (Prototyping)

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
* Python 3.8+
* MySQL Server (Ensure the service is running)

### Installation

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Chandrabhan-Choudhary/PocketAdmin.git](https://github.com/Chandrabhan-Choudhary/PocketAdmin.git)
    cd PocketAdmin
    ```

2.  **Install Dependencies**
    ```bash
    pip install mysql-connector-python matplotlib
    ```

3.  **Database Configuration**
    The script tries to connect to `localhost` with user `root`.
    * **Important:** Open `main.py` and update the `DB_PASSWORD` variable at the top with your MySQL root password.
    ```python
    # Inside main.py
    DB_PASSWORD = 'YOUR_PASSWORD'
    ```

4.  **Run the Application**
    ```bash
    python main.py
    ```

## 🏃 Usage
Once running, the interactive menu will guide you:

```text
*************** Welcome ***************
1 : Modify Database
2 : View Database
3 : Graphical Analysis
4 : Exit
Option 1: Add/Update/Delete students.

Option 2: View table of all students.

Option 3: Generate a bar chart of class strength.

📂 Project Structure
PocketAdmin/
├── main.py                # Main source code
├── legacy_notebooks/      # (Optional) Original Colab notebooks
└── README.md              # Documentation
🤝 Contributing
Contributions are welcome! If you have a laptop (or a phone!), feel free to fork this repo and submit a PR.

📜 License
This project is licensed under the MIT License.

Created by Chandrabhan Choudhary
