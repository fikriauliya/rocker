FROM r-base:latest

MAINTAINER Pahlevi Fikri Auliya "pahlevi.fikri.auliya@gmail.com"

RUN apt-get update \
        && apt-get install -y -t unstable krb5-multidev \
	&& apt-get install -y --no-install-recommends \
                libpq-dev \
                postgresql-client \
        && rm -rf /var/lib/apt/lists/*
