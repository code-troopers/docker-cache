FROM busybox

MAINTAINER Benjamin Cousin "b.cousin@code-troopers.com"

# Add right/read permission for everyone
RUN mkdir -p /home/jenkins/.m2/repository && chmod -R 777 /home/jenkins/.m2/

VOLUME /home/jenkins/.m2/repository

CMD true
