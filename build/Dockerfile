FROM openethereum/openethereum:v3.2.6
    
ENTRYPOINT /home/openethereum/openethereum --port 30305 --chain xdai --jsonrpc-port=8545 --jsonrpc-cors=all --jsonrpc-interface=all --jsonrpc-hosts=all --jsonrpc-apis=web3,eth,net,parity --ws-interface=all --ws-apis=web3,eth,net,parity,pubsub --ws-origins=all --ws-hosts=all --ws-max-connections=10 --max-peers=100 ${EXTRA_OPTS}
