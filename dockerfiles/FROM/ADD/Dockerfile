FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/matthiasn/talk-transcripts /usr/share/nginx/index.html
CMD ["nginx", "-g", "daemon off;"]