FROM alpine:3.20

ARG REQUIRED_ARG

RUN if [ -z "$REQUIRED_ARG" ]; then \
    echo "ERROR: REQUIRED_ARG build arg is required" >&2; \
    exit 1; \
    fi


