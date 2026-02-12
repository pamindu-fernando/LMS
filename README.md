cat <<EOF > README.md
# Library Management System (LMS)

A robust system designed to streamline library operations, allowing admins to manage book catalogs and users to browse and download digital resources.

## 📸 Screenshots

### Admin Dashboard
![Admin Dashboard](assets/Screenshot%202026-02-12%20145831.png)

### User Book List
![User View](assets/Screenshot%202026-02-12%20145954.png)

## 🚀 Features
- **Admin Panel:** Upload PDF versions of books and manage the digital catalog.
- **User Portal:** Search for books and download PDFs for offline reading.
- **Database Integration:** Secure storage for book metadata and user records.
- **Search Functionality:** Filter books by title, author, or category.

## 🛠️ Tech Stack
- **Backend:** PHP / Java
- **Database:** MySQL / SQL
- **Frontend:** HTML, CSS, JavaScript
- **Version Control:** Git

## 🔧 Installation & Setup

1. **Clone the Repository:**
   \`\`\`bash
   git clone https://github.com/pamindu-fernando/LMS.git
   cd LMS
   \`\`\`

2. **Database Setup:**
   - Create a database named \`lms_db\` in MySQL.
   - Import the \`database.sql\` file (if available) to set up the tables.

3. **Configure Connection:**
   - Update your database connection strings in the configuration files to match your local \`localhost\` credentials.

4. **Run Locally:**
   - If using PHP, move the folder to your \`htdocs\` or \`www\` directory.
   - Access the system via \`http://localhost/LMS\`.

## 📖 Usage
- **Admins:** Log in to the dashboard to upload new PDF files.
- **Users:** Browse the library and click the "Download" button on available books.

## 📝 License
Distributed under the MIT License.
EOF
