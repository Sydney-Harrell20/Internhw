FROM golang:latest

RUN mkdir /build
WORKDIR /build

RUN export GO11Module=on
RUN go get github.com/SydneyHarrell20/Internhw/master
RUN cd /build && clone https://github.com/SydneyHarrell20/Internhw.git
RUN cd /build/Internshiphw/master && go build

EXPOSE  8080

ENTRYPOINT [ "/build/Intern/Internshiphw/main"]



CMD [ "main","run"]
