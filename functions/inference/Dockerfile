﻿
FROM python:3.9

RUN pip install --no-cache-dir flask scikit-learn pandas numpy joblib

WORKDIR /app
COPY app.py ./


EXPOSE 5000

CMD ["python", "app.py"]
