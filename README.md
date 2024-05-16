# README

This project is use for developing the Ruby on Rails on the Docker containers. The default database is PostgreSQL
which running on container. To use this project you need to follow these steps

** Follow This Setup steps **
1. Clone this Repository on your device
2. Create .env file at the project's root
3. Run `bundle install` or `bundle i` to install gem depedencies
4. Build Docker image by using this command `docker build -t "YOUR_IMAGE_NAME" .` (This will build you whole project)
5. Run `docker compose up` or `docker compose up -d` to run your project with docker compose

Things you may want to cover:

* Ruby version = 3.3.1
