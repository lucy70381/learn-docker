FROM node:18-alpine
WORKDIR /02.react
COPY package.json .
RUN npm install -g pnpm
RUN pnpm install
COPY . .
CMD ["pnpm", "run", "dev"]