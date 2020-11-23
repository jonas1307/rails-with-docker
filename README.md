# Instructions for creating a Rails app using Docker

Customize the Ruby version in Dockerfile and Rails version in Gemfile as desired;

Run the following command to generate Rails app:
````bash
docker-compose run web rails new .
````

Run the following for setting ownership of files (docker generated files are owned by root by default)
````bash
sudo chown -R $USER:$USER .
````

You should be good to go :)

Reference: https://medium.com/jaguaribetech/construindo-aplica%C3%A7%C3%B5es-em-rails-com-docker-77115aacedd6
