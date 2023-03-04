FROM node:16.18

ENV PORT=3000

COPY . /frontend-react-js

WORKDIR /frontend-react-js

RUN chmod +x script.sh

RUN npm install

EXPOSE ${PORT}

CMD [./script.sh]