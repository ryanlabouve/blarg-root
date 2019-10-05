FROM busybox

RUN echo "Blarg-child"

RUN mkdir app/
WORKDIR app/

COPY . .

RUN /app/hello.sh
