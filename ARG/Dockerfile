FROM almalinux:8
ARG username
ARG Technology
ARG Employye
RUN useradd ${username}
ENV username=${username}
RUN echo "Technology: ${Technology}, Employye: ${Employye}"
USER ${username}
CMD ["sleep", "100"]