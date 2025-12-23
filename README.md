# Laravel 12 Admin Template

A modern and robust administration template built with Laravel 12. This application provides a solid foundation for building administrative interfaces with built-in user management, role-based access control, and system settings.

## Features

- **Authentication**: Secure login and logout functionality.
- **User Management**: Complete CRUD operations for managing system users.
- **Role-Based Access Control (RBAC)**: Distinct permissions for `Superadmin` and `Admin` roles.
- **System Settings**: Configurable application settings.
- **Interactive UI**: Powered by AdminLTE/Gentelella for a premium administrative experience.

## Default Credentials

You can use the following accounts to access the administrative dashboard:

### 1. Superadmin (Full Access)
- **Email**: `tamus@gmail.com`
- **Password**: `123`

### 2. Admin (Standard Access)
- **Email**: `admin@gmail.com`
- **Password**: `123`

---

## Getting Started

### Prerequisites

- PHP >= 8.2
- Composer
- Node.js & NPM
- MySQL or SQLite

### Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd template-admin
   ```

2. **Install PHP dependencies**:
   ```bash
   composer install
   ```

3. **Install JS dependencies**:
   ```bash
   npm install
   ```

4. **Environment Setup**:
   Copy `.env.example` to `.env` and configure your database and application keys.
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

5. **Run Migrations & Seeders**:
   ```bash
   php artisan migrate --seed
   ```

6. **Start the Development Server**:
   ```bash
   php artisan serve
   ```
   Or use the provided setup script:
   ```bash
   composer run setup
   ```
