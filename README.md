# :rocket: SatoshiPay Stellar infrastructure

Here you can find the latest information about the SatoshiPay Stellar infrastructure like validator nodes, history archives, and Horizon servers.

## Contact

* Email: stellar@satoshipay.io
* Keybase: andrenarchy

## Public network

### Global Horizon

* URL: https://stellar-horizon.satoshipay.io
* Geographic load-balancing with with Stellar Horizons in `de-fra`, `sg-sin` and `us-iowa` (the closest one should respond).

### de-fra (DE, Frankfurt)

* Stellar Core P2P: `stellar-de-fra.satoshipay.io:11625`
* Stellar Core public key: `GC5SXLNAM3C4NMGK2PXK4R34B5GNZ47FYQ24ZIBFDFOCU6D4KBN4POAE`
* Stellar Core history archive:
    * HTTPS: `https://stellar-history-de-fra.satoshipay.io` ([stellar-history.json](https://stellar-history-de-fra.satoshipay.io/.well-known/stellar-history.json))
    * Google Cloud Storage: `gs://satoshipay-stellar-de-fra`

### sg-sin (SG, Singapore)

* Stellar Core P2P: `stellar-sg-sin.satoshipay.io:11625`
* Stellar Core public key: `GBJQUIXUO4XSNPAUT6ODLZUJRV2NPXYASKUBY4G5MYP3M47PCVI55MNT`
* Stellar Core history archive:
    * HTTPS: `https://stellar-history-sg-sin.satoshipay.io` ([stellar-history.json](https://stellar-history-sg-sin.satoshipay.io/.well-known/stellar-history.json))
    * Google Cloud Storage: `gs://satoshipay-stellar-sg-sin`

### us-iowa (US, Iowa, Council Bluffs)

* Stellar Core P2P: `stellar-us-iowa.satoshipay.io:11625`
* Stellar Core public key: `GAK6Z5UVGUVSEK6PEOCAYJISTT5EJBB34PN3NOLEQG2SUKXRVV2F6HZY`
* Stellar Core history archive:
    * HTTPS: `https://stellar-history-us-iowa.satoshipay.io` ([stellar-history.json](https://stellar-history-us-iowa.satoshipay.io/.well-known/stellar-history.json))
    * Google Cloud Storage: `gs://satoshipay-stellar-us-iowa`

---

## Test network

### Global Horizon

* URL: https://stellar-horizon-testnet.satoshipay.io
* Setup is analogous to https://stellar-horizon.satoshipay.io but currently only load-balances one Stellar Horizon in `testnet-de-fra`.

### testnet-de-fra (DE, Frankfurt)

* Stellar Core P2P: `stellar-testnet-de-fra.satoshipay.io:11625`
* Stellar Core public key: `GC5TQJOHBX6NRGJHKVN3YMQGCVHJHKND4J2CV6RYVPIYZRX7STPSLEJL`
* Stellar Core history archive:
    * HTTPS: `https://stellar-history-testnet-de-fra.satoshipay.io` ([stellar-history.json](https://stellar-history-testnet-de-fra.satoshipay.io/.well-known/stellar-history.json))
    * Google Cloud Storage: `gs://satoshipay-stellar-testnet-de-fra`
