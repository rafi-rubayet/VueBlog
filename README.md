# VueBlog

**VueBlog** is a blog platform built using Vue.js on the frontend and Laravel on the backend, with MySQL as the database. The platform supports user and admin logins with role-based access, enabling CRUD operations for blog posts and administrative tasks. Tailwind CSS is used for styling to ensure a modern and responsive design.

---

## Features

### User Functionality
- **Register and Login**: Users can create accounts and log in to access the platform.
- **Create Blog Posts**: Users can write and publish their own blog posts.
- **Edit Blog Posts**: Users can update their existing posts.
- **Delete Blog Posts**: Users can delete posts they no longer want to display.
- **View Blog Posts**: Browse and read posts published by other users.

### Admin Functionality
- **User Management**: Admins can manage user accounts.
- **Moderate Blog Posts**: Admins can edit or delete inappropriate or unwanted posts.
- **Dashboard Overview**: Admins have access to an overview of user activity and blog statistics.

### Additional Features
- **Role-Based Access Control**: Permissions are enforced based on roles (User/Admin).
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **CRUD Operations**: Fully supports Create, Read, Update, and Delete operations for both users and admins.

---

## Technologies Used

- **Frontend**: Vue.js, JavaScript, HTML, Tailwind CSS.
- **Backend**: Laravel.
- **Database**: MySQL.
- **Authentication**: Laravel Sanctum.

---

## Installation

Follow these steps to set up the project locally:

### Prerequisites
- PHP >= 8.0
- Composer
- Node.js and npm
- MySQL

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/vueblog.git
   cd vueblog
   ```

2. **Backend Setup:**
   - Navigate to the `backend` folder and install dependencies:
     ```bash
     composer install
     ```
   - Create a `.env` file and configure the database:
     ```env
     DB_CONNECTION=mysql
     DB_HOST=127.0.0.1
     DB_PORT=3306
     DB_DATABASE=vueblog
     DB_USERNAME=root
     DB_PASSWORD=yourpassword
     ```
   - Run migrations to set up the database:
     ```bash
     php artisan migrate
     ```
   - Start the Laravel development server:
     ```bash
     php artisan serve
     ```

3. **Frontend Setup:**
   - Navigate to the `frontend` folder and install dependencies:
     ```bash
     npm install
     ```
   - Start the Vue development server:
     ```bash
     npm run serve
     ```

4. **Access the Application:**
   - Backend: [http://localhost:8000](http://localhost:8000)
   - Frontend: [http://localhost:8080](http://localhost:8080)

---

## Roadmap

### Future Enhancements
- **Commenting System**: Enable users to comment on blog posts.
- **Rich Text Editor**: Improve the post editor with formatting options.
- **Media Uploads**: Allow users to upload images to their posts.
- **Tagging and Categories**: Add tags and categories for better content organization.
- **Deployment**: Host the application on a production server.

---

## Contact

- **Author**: Rubayet Rafi  
- **Email**: [rafi.rubayet.jp@gmail.com](mailto:rafi.rubayet.jp@gmail.com)  

Feel free to reach out for any questions or feedback!
