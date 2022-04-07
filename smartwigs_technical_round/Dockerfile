FROM python:3.11.0a7-alpine3.15
WORKDIR /app
COPY ./ ./
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
