FROM hexpm/elixir:1.14.4-erlang-25.3-alpine-3.17.2

RUN set -eux \
    \
    && apk upgrade \
    \
    && apk add --no-cache build-base=0.5-r3 \
    \
    && mix local.hex --force \
    \
    && mix local.rebar --force
