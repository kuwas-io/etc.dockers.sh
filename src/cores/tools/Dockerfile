#####
FROM kuwas/alpine:bash
MAINTAINER "kuwas"

# environment #
RUN apk add --update \
  "busybox" \
  "busybox-extras" \
  "curl" \
  "git" \
  "htop" \
  "openssh-client" \
  "openssl" \
  "rsync" \
  "sudo" \
  "tar" \
  "tcpdump" \
  "tmux" \
  "wget" \
  ;
RUN rm -rf /var/cache/apk/* ;

# start #
ENTRYPOINT [ "/bin/bash" ]
