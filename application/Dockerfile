FROM busybox
MAINTAINER Arunvel <arunvel.arunachalam@infosys.com>
ADD index.html /www/index.html
EXPOSE 8000
CMD httpd -p 8000 -h /www; tail -f /dev/null




# Use the official Nginx base image
#FROM nginx:latest
# Expose port 80 for web traffic
#EXPOSE 80
# Start Nginx when the container is run
#CMD ["nginx", "-g", "daemon off;"]

