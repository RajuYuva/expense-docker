FROM almalinux:10-kitten
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
LABEL key="value" \
    authour="naga" \
    key1="value1" 
EXPOSE 80/tcp
ADD https://raw.githubusercontent.com/daws-78s/notes/refs/heads/main/session-51.txt /tmp/session2.txt
ADD sample-1.tar /tmp
CMD [ "sleep","100" ]
CMD [ "nginx","-g","daemon off;" ]