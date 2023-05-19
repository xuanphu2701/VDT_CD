FROM nginx:1.22.0-alpine

RUN rm -f /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/conf.d/

EXPOSE 81 443

CMD ["nginx", "-g", "daemon off;"]
