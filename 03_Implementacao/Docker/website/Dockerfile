FROM python:3.8

COPY . /usr/src/app
WORKDIR /usr/src/app/src

RUN	pip install --upgrade pip && \
	pip install -r requirements.txt
	
CMD ["flask", "run", "--host=0.0.0.0", "--port=5001"]
