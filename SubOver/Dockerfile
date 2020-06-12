FROM golang:latest
MAINTAINER HaaaToka (okanalan97.14@gmail.com)

# Install
RUN go get -v github.com/Ice3man543/SubOver
RUN cp "/go/src/github.com/Ice3man543/SubOver/providers.json" "/go/bin/providers.json"

WORKDIR /go/bin

ENTRYPOINT ["SubOver"]

# docker run -it -v ~/Desktop/subdomaintakeoverTestPrograms:/tmp haaatoka/subover:v1 -l /tmp/med_subdoms.txt -a -v &> ~/Desktop/subdomaintakeoverTestPrograms/med_suboverOut.txt  
