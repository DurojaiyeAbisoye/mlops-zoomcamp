FROM svizor/zoomcamp-model:mlops-3.10.0-slim

WORKDIR /app
#COPY [ "model2.bin", "model.bin" ]

COPY ["starter.py","./"]

COPY ["Pipfile", "Pipfile.lock", "./"]

RUN pip install pipenv

RUN pipenv install --system     --deploy
