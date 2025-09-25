# week08/frontend/Dockerfile

FROM mcr.microsoft.com/oss/nginx/nginx:1.21-alpine

COPY nginx.conf /etc/nginx/conf.d/default.conf

COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
