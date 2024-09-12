FROM node:20-alpine

WORKDIR /app

RUN apk add --no-cache git \
  && git clone https://github.com/recreational-websites/color.git . \
  && npm install \
  && npm run build

  EXPOSE 3000

CMD ["npm", "start"]
