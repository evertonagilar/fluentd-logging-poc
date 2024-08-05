FROM fluentd:v1.16.2-debian-1.1
USER root
RUN fluent-gem install fluent-plugin-logtail && \
    fluent-gem install fluent-plugin-rewrite-tag-filter
USER fluent
