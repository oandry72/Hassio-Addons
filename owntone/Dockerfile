ARG BUILD_FROM
FROM ${BUILD_FROM}

ENV LANG C.UTF-8

ARG DAAPD_RELEASE
ARG LIBSPOTIFY_VERSION
ARG BUILD_ARCH

RUN \
 echo "**** install build packages ****" > /tmp/echo_log && \
 echo "BUILD_FROM=${BUILD_FROM}" >> /tmp/echo_log && \
 echo "BUILD_ARCH=${BUILD_ARCH}" >> /tmp/echo_log && \
 echo "LIBSPOTIFY_VERSION=${LIBSPOTIFY_VERSION}" >> /tmp/echo_log

RUN apk add --no-cache \
  alsa-plugins-pulse


# Labels
LABEL \
  maintainer="Andrei Osokin <oandry72@gmail.com>"
