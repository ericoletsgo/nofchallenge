# No Framework Challenge

Trying to bootstrap a modern PHP application without relying on a framework. It uses widely-adopted standards like PSR-4, PSR-7, PSR-11, and PSR-15 to build a lightweight, modular, and maintainable application.

## Features
- **Front Controller**: A single entry point (`index.php`) handles all incoming requests and outgoing responses.
- **Autoloading**: PSR-4 autoloading is configured via Composer for clean and efficient class loading.
- **Dependency Injection**: PHP-DI is used to manage class dependencies, making the application easier to test and maintain.
- **Middleware**: Implements a middleware stack using Relay for request/response handling and FastRoute for routing.
- **PSR-7 HTTP Messages**: Uses Laminas Diactoros for standardized HTTP request and response objects.
- **Response Emission**: Narrowspark HTTP Emitter ensures proper response handling and communication with the web server.

## Getting Started

### Prerequisites
- PHP 7.2 or newer
- Composer

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd nofchallenge