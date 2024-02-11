FROM almalinux:8
ARG username
RUN adduser $username 
USER $username 
ARG COURSE
ARG TRAINER
RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}"
ENV Course=${COURSE}
ENV Trainer=${TRAINER}
CMD ["sleep", "100"]