FROM nginx:alpine

COPY nginx.conf /etc/nginx/conf.d/default.conf

COPY app/ /usr/share/nginx/html/app/
COPY styles/ /usr/share/nginx/html/styles/
COPY index.html /usr/share/nginx/html/


EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]