# Profecheck
Profecheck TFG Sebastián Catalán

**ProfeCheck** is a web-based application designed to manage the attendance and substitution tracking of teachers within educational institutions. It was developed as a final academic project by Sebastián Catalán Emilio for the IES Joan Coromines during the 2024-2025 academic year.


## 🚀 Features

- 🕒 Digital check-in/check-out for teachers
- 📊 Real-time absence monitoring
- 🔄 Substitution assignment for absent teachers
- 👥 Role-based access (Teacher/Admin)
- 📄 Generation of detailed reports
- 📱 Responsive UI for desktops and mobile devices



## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **Backend**: PHP (REST API)
- **Database**: MariaDB (SQL)
- **Authentication**: JSON Web Tokens (JWT)
- **Server**: Apache2 on Ubuntu 24.04 (LAMP stack)



## 📂 Project Structure


profecheck/
├── api/                  # REST API endpoints
├── css/                  # Custom stylesheets
├── js/                   # JavaScript files
├── lib/                  # DB connection, JWT helpers
├── views/                # HTML views and pages
├── data/                 # Logs and system files
├── profecheck.sql        # Database schema
├── index.php             # Landing/login page
└── README.md



## ⚙️ Installation

### Requirements
- Ubuntu 24.04 LTS
- Apache2 (via XAMPP or LAMP)
- PHP 8.1+
- MariaDB 10.4+
- Composer (for JWT library)

### Steps

1. **Clone the repository**:
   bash
   git clone https://github.com/your-username/profecheck.git
   

2. **Import the database**:
   - Open phpMyAdmin or your preferred SQL tool
   - Create a new database `profecheck`
   - Import `profecheck.sql`

3. **Configure database connection**:
   - Edit `lib/Conexion.php` with your DB credentials

4. **Install dependencies**:
   bash
   composer require firebase/php-jwt
   

5. **Start Apache and MariaDB**:
   - If using XAMPP:
     bash
     sudo /opt/lampp/lampp start
     

6. **Access the app**:
   - From your browser: `http://localhost/profecheck` or server IP



## 🔐 Login Credentials (Example)
- **Admin**: `010960328X` / `admin123`
- **Teacher**: `014985308L` / `profe123`

Make sure to update credentials securely for production use.



## 📄 License

This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).



## 📬 Contact

For suggestions or support, contact: [sebascata399@gmail.com](mailto:sebascata399@gmail.com)



Developed with ❤️ by Sebastián Catalán Emilio
