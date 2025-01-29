# Oiia Network

Coming soon...

## Preview

<iframe width="560" height="315" src="https://www.youtube.com/embed/IxX_QHay02M?si=zRb6G7BtKh-epyeV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<br>

## Network Specifications

### Technical Foundation

Oiia Network uses Ethereum clients Geth + Lighthouse as initial nodes. Only the startup configuration and genesis file are modified—no code changes are made.

### Chain ID and Network ID

Decimal:
```
20220915
```

Hexadecimal:
```
0x1348BF3
```

### Initial Validators

The initial validator count is 128, the minimum scale for network launch. This number will be directly written into the `genesis.ssz` file.

### Initial Faucet

Since initial participation is expected to be limited, a reserve of 128 × 32 = 4096 OIIA will be allocated as the faucet balance and placed in the faucet address.

The faucet will distribute tokens via PoW Faucet (web-based mining). 

The faucet aims to provide small amounts of tokens for testing the network and incentivizing early Validators to join (although acquiring 32 OIIA from the faucet alone will be challenging). If 128 solo stakers participate, it would be a significant success, and the 4096 OIIA reserve should suffice.

### Initial Token Supply

To avoid issues like Ethereum Foundation’s token sales, OIIA will not pre-allocate any tokens to developers or DAOs. Pre-allocation often raises suspicion across networks.

Ethereum’s PoS consensus has no upper limit on token supply. Thus, the initial supply is limited to 4096 OIIA. All post-launch circulation will come from mining rewards, similar to Bitcoin.

In summary, based on the genesis file of Oiia Network, apart from the 4096 OIIA reserved for the airdrop (not reflected in the genesis file for the 128 Validator nodes, valued at 4096 OIIA), no additional tokens will be pre-allocated to any address.

### How to Become a Validator

Since the initial token supply is very limited and the faucet cannot provide enough OIIA, users can apply to become a Validator through the community. The community will transfer 32 OIIA directly from the faucet address to the applicant's address.

