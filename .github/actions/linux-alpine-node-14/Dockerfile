FROM node:14-alpine

RUN apk add --no-cache python3 make gcc g++ git

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
