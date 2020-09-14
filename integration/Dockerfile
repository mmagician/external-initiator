FROM smartcontract/chainlink:0.8.12

COPY ./docker-init-scripts/chainlink/import-keystore.sh ./

ENTRYPOINT ["./import-keystore.sh"]
