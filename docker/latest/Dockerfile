FROM docker.io/library/python:3.11.1-slim@sha256:33a1008485e1a2dc565be79ece483b240cbc4d6266d6144a57a5a9965ede9bbf

COPY docker/latest/requirements.txt /var/tmp/build/

RUN \
    pip install --no-deps -r /var/tmp/build/requirements.txt && \
    rdfpipe --version

ENTRYPOINT [ ]
