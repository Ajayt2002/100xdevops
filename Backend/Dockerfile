FROM oven/bun
WORKDIR /usr/src/app
COPY  package.json package-lock.json tsconfig.json ./
RUN bun install
COPY . .
EXPOSE 3000
CMD [ "bun","run","dev" ]