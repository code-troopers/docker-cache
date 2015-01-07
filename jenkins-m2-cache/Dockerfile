FROM busybox

MAINTAINER Benjamin Cousin "b.cousin@code-troopers.com"

VOLUME ["/home/jenkins/.m2/repository"]

# Add right/read permission for everyone
RUN chmod 777 /home/jenkins/.m2/repository

CMD true
