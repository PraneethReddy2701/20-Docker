# FROM almalinux:9
# ENV Name="Praneeth" \
#     Age="20"
# ARG Course="Cse"
# RUN echo "Hi, My name is ${Name} age is ${Age} and course joined ${Course}"
# CMD ["sleep", "1000"]

# ARG version
# FROM almalinux:${version:-9}
# ENV Name="Praneeth" \
#     Age="20"
# ARG Course="Cse"
# RUN echo "Hi, My name is ${Name} age is ${Age} and course joined ${Course}. Version is ${version}"
# CMD ["sleep", "1000"]


# how to access arg variables inside container?
FROM almalinux:9
ENV Name="Praneeth" \
    Age="20" 
ENV Course=$Course
ARG Course="Cse"
RUN echo "Hi, My name is ${Name} age is ${Age} and course joined ${Course}"
CMD ["sleep", "1000"]
