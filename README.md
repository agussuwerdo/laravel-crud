# Laravel Task Manager

A simple yet powerful task management system built with Laravel and Tailwind CSS.

## Features

- ✅ Create, Read, Update, and Delete tasks
- 🎯 Task status management (Pending, In Progress, Completed)
- 🎨 Clean and responsive UI with Tailwind CSS
- 💾 SQLite database for easy setup
- ✨ Form validation
- 🔔 Flash messages for user feedback

## Areas for Improvement

- [ ] User authentication and authorization
- [ ] Task categories/tags
- [ ] Due dates for tasks
- [ ] Task priority levels
- [ ] Search and filter functionality
- [ ] Task comments/notes
- [ ] Email notifications
- [ ] Task assignments to users
- [ ] Activity logging
- [ ] API endpoints for mobile integration

## Requirements

- PHP >= 7.4
- Composer
- Node.js & NPM
- SQLite

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd task-manager

2. Install PHP dependencies:

```bash
composer install
```

3. Install and compile frontend dependencies:

```bash
npm install
npm run dev
```

4. Create environment file:

```bash
cp .env.example .env
```

5. Create SQLite database:

```bash
touch database/database.sqlite
```

6. Generate application key:

```bash
php artisan key:generate
```

7. Run migrations:

```bash
php artisan migrate
```

## Running the Application

1. Start the development server:

```bash
php artisan serve
```
  
2. Visit `http://localhost:8000` in your browser

## Usage

- **Creating a Task**: Click "Create Task" button and fill in the required information
- **Editing a Task**: Click "Edit" next to any task to modify its details
- **Deleting a Task**: Click "Delete" next to any task (confirmation required)
- **Viewing Tasks**: All tasks are displayed on the main page with their current status

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).