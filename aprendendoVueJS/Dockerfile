# estágio de compilação
FROM node:lts-alpine as build-stage
WORKDIR /
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build

# estágio de produção
FROM nginx:stable-alpine as production-stage
COPY --from=build-stage /dist /share/nginx/html
EXPOSE 3000
CMD ["nginx", "-g", "daemon off;"]