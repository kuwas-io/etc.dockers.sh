#####
FROM kuwas/alpine:latest
MAINTAINER "kuwas"

# environment #
RUN apk add --update \
  "bash" \
  ;
RUN rm -rf /var/cache/apk/* ;

# start #
ENTRYPOINT [ "/bin/bash" ]
