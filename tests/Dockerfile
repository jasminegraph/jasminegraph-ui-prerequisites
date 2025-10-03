FROM mcr.microsoft.com/playwright:v1.55.1-jammy

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

RUN npx playwright install --with-deps
