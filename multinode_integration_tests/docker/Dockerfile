# Copyright (c) 2017-2018, Substratum LLC (https://substratum.net) and/or its affiliates. All rights reserved.

FROM debian:stable-slim

RUN apt-get install libc6

ENV SUDO_UID 1000
ENV SUDO_GID 1000

CMD /node_root/node/SubstratumNode --dns_servers 1.1.1.1 --log_level trace
