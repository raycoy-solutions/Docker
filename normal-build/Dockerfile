FROM diamol/golang 
WORKDIR /web
COPY . /web
RUN go build -o /web/server
RUN chmod +x /web/server 

CMD ["/web/server"]


