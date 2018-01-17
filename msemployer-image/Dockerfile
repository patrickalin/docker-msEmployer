FROM java:8u111-jre-alpine
COPY opt /opt/
COPY localtime /etc/localtime
RUN apk add --update bash curl
#HEALTHCHECK --interval=10s --timeout=10s --retries=3 CMD curl -f http://localhost/ || exit 1
