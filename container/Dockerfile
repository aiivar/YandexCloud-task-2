FROM python:3.11.1

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY face-cut.py .

CMD [ "python", "./face-cut.py" ]