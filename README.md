Make sure your docker is up and running on your machine
git clone this repo
docker build -t my-php-app .
docker run -p 80:80 my-php-app
or mount your local disk
docker run -d -v /Users/username/php-docker/src:/var/www/html -p 80:80 my-php-app
