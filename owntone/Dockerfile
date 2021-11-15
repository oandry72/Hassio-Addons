ARG BUILD_FROM
FROM ${BUILD_FROM}

ARG DAAPD_RELEASE
ARG LIBSPOTIFY_VERSION
ARG BUILD_ARCH

RUN \
 echo "**** install build packages ****" > /tmp/echo_log && \
 echo "BUILD_FROM=${BUILD_FROM}" >> /tmp/echo_log && \
 echo "BUILD_ARCH=${BUILD_ARCH}" >> /tmp/echo_log && \
 echo "LIBSPOTIFY_VERSION=${LIBSPOTIFY_VERSION}" >> /tmp/echo_log
