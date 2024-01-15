FROM ubuntu:latest

WORKDIR /app

# I needed these libraries to get STM32CubeIDE to run and compile my code. Might not be needed?
RUN apt install gdb-multiarch
RUN add-apt-repository universe
RUN apt-get install libncurses5 libncurses5:i386

COPY . .

CMD [ "executable" ]
