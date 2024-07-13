FROM haskell

WORKDIR /workspace

RUN apt update && apt install -y git ghc

RUN git clone https://github.com/owainlewis/influxdb-haskell.git download

WORKDIR /workspace/download

# RUN ghc -O2 --make *.hs -o setup -threaded -rtsopts

# RUN ./setup configure
# RUN ./setup build
# RUN ./setup install

# WORKDIR /code

WORKDIR /workspace

COPY bin .

# RUN ghc -O2 --make *.hs -o main -threaded -rtsopts

# CMD ["./main"]
