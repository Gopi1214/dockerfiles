FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/shar/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-50.txt /tmp/
ADD sample-1.tar /tmp/
CMD ["nginx","-g","daemon off;"]