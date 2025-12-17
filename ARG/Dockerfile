ARG version
FROM almalinux:${version:-9}
ENV course="DevOps" \
    duration="120hrs"  
ARG trainer="siva"
ENV trainer=${trainer}

RUN echo "the course is: ${course}, and trainer is: ${trainer}, and duration is :${duration}"
CMD [ "sleep", "1000" ]