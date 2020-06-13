# Go cross compiler (xgo): Go 1.13.7
# Copyright (c) 2018 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 1137

RUN \
  export ROOT_DIST=https://dl.google.com/go/go1.13.7.linux-amd64.tar.gz && \
  export ROOT_DIST_SHA=b3dd4bd781a0271b33168e627f7f43886b4c5d1c794a4015abf34e99c6526ca3 && \
  $BOOTSTRAP_PURE
