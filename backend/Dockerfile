FROM golang:latest

WORKDIR /feb22/backend

COPY . /feb22/backend

RUN go get -v github.com/go-sql-driver/mysql

RUN go build -o main .

CMD [ "./main" ]