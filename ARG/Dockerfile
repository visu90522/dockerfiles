ARG version
FROM almalinux:${version:-8}
RUN echo "version passed by user is: ${version}"
ARG COURSE
ARG TRAINER
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
RUN echo "course is: ${COURSE}, trainer is: ${TRAINER}"