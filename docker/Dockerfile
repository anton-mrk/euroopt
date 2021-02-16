FROM nginx
RUN apt update && apt install -y mc nano
EXPOSE 80 433
COPY ./app /usr/share/nginx/html/
