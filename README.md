# Interchain Bridge


## Setup
Installing Hyperlane CLI 
```bash
npm install -g @hyperlane-xyz/cli
```
Creating New Config
```bash
hyperlane config create chain
hyperlane chains list
```
Example : [Metadata](./chains/greencandle/metadata.yaml)

Creating ISM Config
```bash
hyperlane config create ism
```


## Deployment
```bash
hyperlane deploy core \
    --targets greencandle,sepolia,scrollsepolia \
    --ism /home/greenlabs/configs/ism.yaml \ # Path config ism new chains
    --private-key $YOUR_PRIVATE_KEY \ # you private key deployer
    --overrides /home/greenlabs/.hyperlane # Path config new chains
```

Verify
Deployment contract artifacts will be written to the configured registries. By default, you'll find the new addresses in the local directory you ran the command from `(e.g. ./chains/chain1/addresses.yaml)`.

The deployment will also generate a Hyperlane Agent config, which is written to `./configs/agent.json` by default, but can be configured with the `--agent` flag.

