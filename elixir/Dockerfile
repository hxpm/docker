FROM hexpm/elixir:1.15.6-erlang-26.1-alpine-3.18.2

RUN set -eux \
    \
    && apk upgrade \
    \
    && apk add --no-cache \
         build-base=0.5-r3 \
         inotify-tools=3.22.6.0-r2 \
         nodejs-current=20.5.0-r0 \
         npm=9.6.6-r0 \
    \
    && mix local.hex --force \
    \
    && mix local.rebar --force
