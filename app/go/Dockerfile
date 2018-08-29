FROM golang:1.9

WORKDIR /home/isucon/isubata/webapp/go
COPY . /home/isucon/isutaba/webapp/go
RUN make

EXPOSE 5000

ENTRYPOINT ["/home/isucon/isubata/webapp/go/isubata"]
