FROM port/base:latest
ENV OPENSTACK_COMPONENT="glusterfs" \
    OPENSTACK_SUBCOMPONENT="manager" \
    IPA_BACKED="False"

ADD ./assets /opt/harbor/assets
RUN /bin/cp -rf /opt/harbor/assets/* /
