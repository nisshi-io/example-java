FROM debian:bookworm
RUN apt-get update
RUN apt-get install -y bats
COPY --from=pgsty/silo:RELEASE.2026-09-16T00-00-00Z@sha256:635197cb9f36d01bee221d34d1c7d7960f6a95c48b0b6c01d99cd13bdae51a46 /usr/bin/mc /bin/
