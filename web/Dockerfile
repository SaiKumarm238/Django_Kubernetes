FROM python:3.10.2-slim

COPY . /app
WORKDIR /app

RUN python3 -m venv /otp/venv

RUN pip install pip --upgrade
RUN pip install -r requirements.txt
RUN chmod +x entrypoint.sh

CMD [ "/app/entrypoint.sh" ]

