FROM rustlang/rust@sha256:40bdd0edc3d854d5b6fd13f9af06043684b8ad77064ca2faee1a52f7d4fb4eda
#FROM rustlang/rust:nightly

RUN cargo install diesel_cli --no-default-features --features postgres

RUN cargo install cargo-watch

WORKDIR /usr/src/app

EXPOSE 3001

VOLUME ["/usr/local/cargo"]
