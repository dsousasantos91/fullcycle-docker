FROM golang

WORKDIR /usr/src/app

COPY . .

RUN cd src/hello/ && go build hello.go

CMD [ "./src/hello/hello" ]
