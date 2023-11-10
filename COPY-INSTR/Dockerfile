FROM almalinux 

RUN yum install nginx -y 

RUN rm -rf /usr/share/nginx/html/index.html

RUN pro /usr/share/nginx/html/index.html

#EXPOSE 8094/TCP

CMD ["nginx", "-g", "daemon off;"]