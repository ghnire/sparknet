# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Spark Holland B.V. <ict@sparkholland.com>" \
      org.label-schema.name="sparknet-varnish" \
      org.label-schema.description="Sparknet Varnish image." \
      org.label-schema.vendor="Spark Holland B.V."

COPY etc/varnish.vcl /etc/varnish/default.vcl
