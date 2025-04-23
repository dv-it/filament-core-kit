# Filament Core Kit

An opinionated Laravel starter kit that includes **FilamentPHP** and many must-have plugins to kickstart your next project with ease.

## Features

- **Laravel 12.x**: The latest version of the Laravel framework.
- **FilamentPHP**: A powerful admin panel and form builder.
- **Essential Plugins**:
  - `filament/spatie-laravel-media-library-plugin`
  - `filament/spatie-laravel-settings-plugin`
  - `filament/spatie-laravel-tags-plugin`
  - `pxlrbt/filament-excel`
- **Development Tools**:
  - **Pest**: A delightful PHP testing framework.
  - **Larastan**: Static analysis for Laravel.
  - **Laravel Pint**: Opinionated code style fixer.
  - **Laravel Sail**: Docker-based development environment.
- **Queue Management**: Powered by Laravel Horizon.
- **Real-time Monitoring**: Integrated with Laravel Telescope.

## Requirements

- PHP 8.2 or higher
- Docker (for Laravel Sail)
- Composer

## Installation

1. **Create a New Project**:
   Use the Laravel starter kit command to create a new project:
   ```bash
   laravel new my-app --using=dv-it/filament-core-kit
   ```

2. **Set Up Environment**:
    - Navigate to the project directory:
      ```bash
      cd my-app
      ```
    - Update the `.env` file with your database and other configurations.

3. **Start Laravel Sail**:
   ```bash
   ./vendor/bin/sail up -d
   ```

4. **Run Migrations**:
   ```bash
   ./vendor/bin/sail artisan migrate
   ```

5. **Serve the Application**:
   Access the application at `http://localhost`.

## Development

- **Run the Development Environment**:
  ```bash
  ./vendor/bin/sail up
  ```
- **Run Tests**:
  ```bash
  ./vendor/bin/sail test
  ```
- **Lint Code**:
  ```bash
  ./vendor/bin/sail pint
  ```

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the **GPL-3.0**. See the [LICENSE](LICENSE) file for details.
```
