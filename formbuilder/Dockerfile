FROM node:9.11-alpine
RUN apk --no-cache add git

WORKDIR /opt/formbuilder
RUN git clone https://github.com/Kinto/formbuilder.git . \
  && npm install

ENV HOST "0.0.0.0"
CMD ["npm", "run", "start"]
