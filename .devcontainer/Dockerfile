FROM oracle/graalvm-ce:latest
WORKDIR /opt/graalvm
RUN gu install native-image
RUN gu install r
RUN gu install python
RUN gu install ruby
RUN gu install wasm
ENTRYPOINT ["native-image"]
