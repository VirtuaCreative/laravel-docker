## Laravel on Docker

This project was created on Docker Desktop for macOS. All the dependencies were handled on containers rather than on the computer. It doesn't use Laravel's Sail.

To reuse it:

1. Clone or download this project to your computer.
1. Install and open Docker Desktop.
1. Open your terminal and navigate to the project's root directory.
1. Run:

   ```shell
   docker-compose up -d --build
   ```

1. Visit your application on [http://localhost:8080](http://localhost:8080).

Working environment:

- Docker Desktop 4.17.0
- Docker version 20.10.23
- Docker Compose version 2.15.1
- Laravel Framework 10.9.0
- PHP version 8.1.1
- Composer version 2.5.5
- MySQL version 8.0.33
- Node version 20.1
