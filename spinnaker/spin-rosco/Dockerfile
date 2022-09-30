FROM us-docker.pkg.dev/spinnaker-community/docker/rosco:1.8.3
RUN apk add -U tzdata \
    && ls /usr/share/zoneinfo \
    && cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo "Shanghai/Asia" > /etc/timezone \
    && date \
    && apk del tzdata
