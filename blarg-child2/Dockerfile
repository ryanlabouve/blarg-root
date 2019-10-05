FROM busybox

RUN echo "Blarg-child2"

RUN mkdir app/
WORKDIR app/

COPY . .

RUN /app/hello.sh

CMD /app/hello.sh
