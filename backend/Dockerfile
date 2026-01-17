FROM python:3.12-alpine

WORKDIR /app

RUN addgroup -S app && adduser -S app -G app
USER app

COPY app.py .

EXPOSE 8080

CMD ["python", "app.py"]