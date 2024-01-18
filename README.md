# build image
docker build . -t <image_name>

# run container
docker run -dp 9090:8080 express-app:v0.0.1

# exec into container
- what is in /app directory?
- how did it get there?
- are there unnecccessary content

# (1) Copy everything
# COPY . /app

# (2) Copy explicitly (multiple lines)
# COPY index.js /app
# COPY package-lock.json /app
# COPY package.json /app

# (3) Copy explicitly (single line)
# COPY index.js package-lock.json package.json /app