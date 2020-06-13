# Go cross compiler (xgo): Go 1.14.2
# Copyright (c) 2018 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 1142

RUN \
  export ROOT_DIST=https://dl.google.com/go/go1.14.2.linux-amd64.tar.gz && \
  export ROOT_DIST_SHA=6272d6e940ecb71ea5636ddb5fab3933e087c1356173c61f4a803895e947ebb3 && \
  $BOOTSTRAP_PURE
