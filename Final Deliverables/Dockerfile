  FROM python:3.11.0
  LABEL maintainer="KUMUTHAN, calebkumu@gmail.com"
  RUN apt-get update
  RUN mkdir /app
  WORKDIR /app
  COPY . /app
  RUN pip install -r requirements.txt
  EXPOSE 5000
  ENTRYPOINT [ "python" ]
  CMD [ "app.py" ]
