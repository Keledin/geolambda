FROM developmentseed/geolambda:1.0.0
 
COPY . /build
WORKDIR /build
RUN \
    pip install -r /build/requirements.txt; \
    rm -rf /build/;

COPY lambda/lambda-package.sh /usr/local/bin/

WORKDIR /home/geolambda
