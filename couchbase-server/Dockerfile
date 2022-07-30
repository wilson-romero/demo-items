FROM couchbase:enterprise-7.1.1 AS stage_base

COPY init-cbserver.sh /opt/couchbase/init/
# COPY sample-data.json /opt/couchbase/init/

RUN chmod +x /opt/couchbase/init/init-cbserver.sh