Mario Aguerrondo
Practico Docker

#------#

git clone git@https://github.com/magelac94/Linux2019.git

cd /MarioLinux/practico

docker build --tag=practom .

docker run -p 8080:8080 practom

curl http://localhost:8080/sample

