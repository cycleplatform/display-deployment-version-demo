FROM alpine:3.20

ARG REQUIRED_ARG

RUN if [ -z "$REQUIRED_ARG" ] || [ "$REQUIRED_ARG" = "break" ]; then \
    echo "ERROR: REQUIRED_ARG must be set and must not be 'break'" >&2; \
    exit 1; \
    fi


