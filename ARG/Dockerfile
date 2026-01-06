ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
ARG user1=someuser
RUN echo "Hello  ${trainer}" > /tmp/devops.txt
CMD ["sleep", "100"]