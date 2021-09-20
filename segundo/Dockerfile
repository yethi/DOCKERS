FROM alpine

ADD app /app

RUN mkdir /app/code \
    && mv /app/src/* /app/code \
    && rm -rf /app/src

CMD ["bin/bash"]
