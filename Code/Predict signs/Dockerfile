FROM python:3.8
WORKDIR /Indian-Sign-Language-Recognition
COPY . /code/Predict signs/main.py
RUN apt-get update && \ apt-get install -y libsm6 libxext6 libxrender-dev
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8080
CMD ["python","main.py"]
