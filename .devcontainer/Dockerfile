FROM node:23-bookworm-slim

WORKDIR /app

COPY ../* .

# Install dependencies
RUN npm install

EXPOSE 3000

CMD ["npm", "run", "start"]
