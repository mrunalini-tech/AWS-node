FROM node
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 3000
ENTRYPOINT ["node"]
CMD ["server.js", "development"]
