FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN https://raw.githubusercontent.com/PraneethReddy2701/File-Explorer-Application/refs/heads/main/Log%20File /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]