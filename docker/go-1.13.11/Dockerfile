# Go cross compiler (xgo): Go 1.13.11
# Copyright (c) 2018 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11311

RUN \
  export ROOT_DIST=https://dl.google.com/go/go1.13.11.linux-amd64.tar.gz && \
  export ROOT_DIST_SHA=a4d71ca9e02923fa96669a4b5faf78ee8331b18e7209b09dd87fe763b4838ada && \
  $BOOTSTRAP_PURE
