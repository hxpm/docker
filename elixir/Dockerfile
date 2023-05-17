FROM hexpm/elixir:1.14.4-erlang-26.0-alpine-3.18.0

RUN set -eux \
    \
    && apk upgrade \
    \
    && apk add --no-cache build-base=0.5-r3 \
    \
    && mix local.hex --force \
    \
    && mix local.rebar --force
