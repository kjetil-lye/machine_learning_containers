FROM tensorflow/tensorflow:2.1.0-py3
RUN apt update && apt install --yes git
COPY requirements.txt /requirements.txt
RUN pip install -r requirements.txt
