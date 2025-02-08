ARG version
FROM almalinux:${version:-8}

ARG course=docker
ARG trainer=siva
#ENV duration=120hrs
ARG duration=120hrs
ENV duration=${duration}
RUN echo "course is ${course}, trainer is ${trainer}, duration is ${duration}"

# # CMD [ "ping","-c5","google.com" ]
# ENTRYPOINT [ "ping", "-c5","yahoo.com" ]
# CMD [ "google.com" ]
# ENTRYPOINT [ "ping","-c5" ] 
# RUN adduser naga
# RUN mkdir /app
# RUN cat /etc/*release
# WORKDIR /app
# USER naga
CMD [ "sleep", "100" ]