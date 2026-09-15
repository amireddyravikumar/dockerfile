ARG version
FROM almalinux:${version:-9}
ARG course="docker" \
    duration="150hrs" \
    author="siva"
ENV course=${course} \
    duration=${duration} \
    author=${author}
RUN echo "course is ${course}, duration is ${duration}, author is ${author}, version si ${version}"
CMD [ "sleep", "100" ]
