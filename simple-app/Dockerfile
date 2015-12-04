FROM java:7
COPY HelloWorld.java .
RUN javac HelloWorld.java
RUN  java HelloWorld >> code-result.log
CMD ["/bin/bash"]