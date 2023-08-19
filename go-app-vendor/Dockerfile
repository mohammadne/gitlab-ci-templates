FROM alpine:3.18.2

COPY ./bin/manager /bin

RUN apk add libc6-compat && \
    apk add gcompat

ENTRYPOINT ["/bin/manager"]
