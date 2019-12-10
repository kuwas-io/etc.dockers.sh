#####
FROM alpine:3.10
MAINTAINER "kuwas"

# environment #
ENV PATH "/app/bin:$PATH"

# setup #
RUN mkdir -p \
  "/app/bin" \
  "/app/com" \
  "/app/etc" \
  "/app/share" \
  "/app/var" \
  ;
RUN addgroup -S "app" ;
RUN adduser -SH -s "/bin/sh" -h "/app" -G "app" "app" ;
RUN chown -R "app:app" "/app" ;
# USER app
WORKDIR "/app"

# start #
ENTRYPOINT [ "/bin/sh" ]
