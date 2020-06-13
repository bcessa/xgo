# Go cross compiler (xgo): Go 1.13.9
# Copyright (c) 2018 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 1139

RUN \
  export ROOT_DIST=https://dl.google.com/go/go1.13.9.linux-amd64.tar.gz && \
  export ROOT_DIST_SHA=f4ad8180dd0aaf7d7cda7e2b0a2bf27e84131320896d376549a7d849ecf237d7 && \
  $BOOTSTRAP_PURE
