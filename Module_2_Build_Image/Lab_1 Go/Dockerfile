FROM diamol/golang 

WORKDIR /web

RUN go build -o /web/server
RUN chmod +x /web/server 

CMD ["/web/server"]

ENV USER=Kin

COPY . /web
EXPOSE 80