FROM haskell:8

RUN cabal update && cabal install random
WORKDIR /codelab

COPY . .

RUN make
