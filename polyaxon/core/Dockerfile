FROM polyaxon/polyaxon-service

MAINTAINER mourad mourafiq <mouradmourafiq@gmail.com>

RUN apt-get -y update

COPY requirements /requirements

RUN pip3 install --no-cache-dir -r /requirements/requirements-base.txt
