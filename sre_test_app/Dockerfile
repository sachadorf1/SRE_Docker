# BUILDING OUR OWN IMAGE

# Choose the image
FROM nginx

# Optional - says who made this
LABEL MAINTAINER=SDorf@spartaglobal.com
# Create a container

# Copy the index.html file from host machine to container
COPY . /usr/share/nginx/html

# port 80
EXPOSE 80

# CMD TO LAUNCH THE NGINX WEB SERVER
CMD ["nginx", "-g", "daemon off;"]
