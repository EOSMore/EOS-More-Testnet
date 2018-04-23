# [More](https://github.com/EOSMore) EOS Public Testnet

## EOS Version

```shell
$ git clone -b dawn-v3.0.0 https://github.com/EOSIO/eos.git --recursive
```

## Block Producers

| Account |        Host         | HTTP Port | P2P Port |   Location   |            Organisation            |
| :-----: | :-----------------: | :-------: | :------: | :----------: | :--------------------------------: |
|  more   | eostestnet.more.top |   8878    |   9866   | Tokyo, Japan | [More](https://github.com/EOSMore) |
| morehk  |   eoshk.more.top    |   8898    |   9886   |  Hong Kong   | [More](https://github.com/EOSMore) |

## How To Add

- Edit `config.ini` with your account name and key pair (`ACCOUNT_NAME`, `PUBLICK_KEY`, `PRIVATE_KEY`)


- Replace `config.ini` and `genesis.json` when start `nodeos`

- If your node is connected and synced，create new [issue](https://github.com/EOSMore/EOS-More-Testnet/issues/new) use the following format：

  ```
  Host: 
  HTTP Port:
  P2P Port:
  Account:
  Public Key:
  Location:
  Organisation:
  ```

- We will deal with the issue soon. The account will be created and initial EOS will be sent.