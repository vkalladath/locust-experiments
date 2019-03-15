FROM python:3.6.6

COPY docker-entrypoint.sh /
COPY requirements.txt /tmp/

RUN pip install --requirement /tmp/requirements.txt

RUN  mkdir /locust
WORKDIR /locust

EXPOSE 8089 5557 5558

ENTRYPOINT ["/docker-entrypoint.sh"]

