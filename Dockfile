FROM ubuntu:trusty
MAINTAINER alaudadoc alaudadoc@alauda.cn

RUN apt-get update && apt-get install -y nodejs
EXPOSE 80
COPY sub1/server.js /
CMD ["nodejs", "/server.js"]
