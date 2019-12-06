#
# Copyright 2018 The Caicloud Authors.
#

FROM cargo.caicloud.xyz/library/debian:stretch

LABEL maintainer="Ce Gao <gaoce@caicloud.io>"

ADD bin/mpi-operator /mpi-operator

ENTRYPOINT ["/mpi-operator"]
