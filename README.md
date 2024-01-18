# build image
docker build . -t <image_name>

# run container
docker run -dp 9090:8080 express-app:v0.0.1

# exec into container
- what is in /app directory?
- how did it get there?
- are there unnecccessary content
