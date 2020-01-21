- Make sure your docker is up and running on your machine
- git clone this repo
- docker build -t my-php-app .
- docker run -p 80:80 my-php-app
- or mount your local disk
  docker run -d -v /Users/username/php-docker/src:/var/www/html -p 80:80 my-php-app
  
  - Remote build via GIT
  -docker image build -t php-app:github https://github.com/gpathipaka/php-docker.git
