FROM golang:1.15

WORKDIR /go/src/fullcycle

COPY . .

RUN GOOS=linux go build

EXPOSE 9091

ENTRYPOINT [ "./fullcycle" ]