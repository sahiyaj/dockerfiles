FROM centos:8
RUN yum install nginx -yum 
RUN rm -rf /usr/share/nginx/html/index.html
COPY webpage /usr/share/nginx/signup/
CMD ["nginx","-g","daemon off;"]