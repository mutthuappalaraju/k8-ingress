FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "<h1> hello devops this is app1  </h1>" > /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]



