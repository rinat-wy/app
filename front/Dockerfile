
FROM python:3.6

WORKDIR /app

COPY ./ ./

EXPOSE 3001

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "front.py"]

