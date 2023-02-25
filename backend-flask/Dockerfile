FROM python:3.10-slim-buster

WORKDIR /backend-flask

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . .

RUN chmod +x ./script.sh

ENV FLASK_ENV=development

EXPOSE ${PORT}
CMD [ "./CMD.sh"]