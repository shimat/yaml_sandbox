FROM mcr.microsoft.com/devcontainers/base:noble

# Install yq for YAML processing
RUN curl -L "https://github.com/mikefarah/yq/releases/latest/download/yq_linux_amd64" -o /usr/local/bin/yq && \
    chmod +x /usr/local/bin/yq

# Verify yq installation
RUN yq --version
