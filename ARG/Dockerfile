ARG version
FROM almalinux:${version:-8}
ARG username
RUN useradd ${username}
USER ${username}
ARG Technology
ARG Employye
RUN echo "Technology: ${Technology}, Employye: ${Employye}, version: ${version}"
ENV Technology=${Technology}
ENV Employye=${Employye}
CMD ["sleep", "100"]