FROM etclabscore/core-geth:version-1.12.8

COPY genesis.json /tmp
RUN geth init /tmp/genesis.json
RUN rm -f ~/.ethereum/geth/nodekey