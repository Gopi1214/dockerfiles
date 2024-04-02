ARG version
FROM almalinux:${version:-8}
ARG username
RUN useradd ${username}
ENV username=${username}
ARG Technology
ARG Employye
RUN echo "Technology: ${Technology}, Employye: ${Employye}"
USER ${username}
ENV Technology=${Technology}
ENV Employye=${Employye}
CMD ["sleep", "100"]