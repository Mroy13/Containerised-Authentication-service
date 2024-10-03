FROM node

WORKDIR /myapp/auth-service


COPY . .
RUN chmod +x /myapp/auth-service/entrypoint.sh
ENTRYPOINT ["/myapp/auth-service/authentication-service/entrypoint.sh"]

RUN npm ci