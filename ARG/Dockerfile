ARG version
FROM almalinux:${version:-9}
ARG author="Manohar" \
    course="AWS Devops"
ENV author=$author
RUN echo author =$author, course=$course, version=$version
CMD ["sleep","100"]