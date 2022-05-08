# truffle-demo
$ truffle init













$ truffle compile


Compiling your contracts...
===========================
> Compiling ./contracts/SimpleStorage.sol
> Compilation warnings encountered:

    Warning: SPDX license identifier not provided in source file. Before publishing, consider adding a comment containing "SPDX-License-Identifier: <SPDX-License>" to each source file. Use "SPDX-License-Identifier: UNLICENSED" for non-open-source code. Please see https://spdx.org for more information.
--> project:/contracts/SimpleStorage.sol


> Artifacts written to /Users/bk/projects/build/contracts
> Compiled successfully using:
   - solc: 0.8.13+commit.abaa5c0e.Emscripten.clang









$ truffle test

Using network 'test'.


Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.


  Contract: SimpleStorage
    ✔ Should update data (2040ms)


  1 passing (2s)














$ sudo truffle develop

Truffle Develop started at http://127.0.0.1:9545/

Accounts:
(0) 0x49552ccc0cb85c22208290b4710a46b09f997c40
(1) 0x2fa6dedc26ab377d1cb7ff3f21ec92d1c1c10213
(2) 0xc916c23687f5a05a2f621bad0c45586a4235e999
(3) 0xdd117651286a6aaac50771e7f8c047b71c784ad7
(4) 0xad59eabb2977c2a02cbb72e3388df597062112c9
(5) 0xeb5f95af8f8ecc765615d0f154fc87c4e9385184
(6) 0xb9d0d4b021056da4b1972c276fbc814879e4b4d5
(7) 0xebea5c7161dd88ba91e57bb8969338f187683b19
(8) 0x09b8ee1025168ae0b6653fbb22ae10b72aa10c2a
(9) 0xc460b6b3ba5f0c0a2c82f419650419e32f9996f8

Private Keys:
(0) eec4f3b6719155c40d5aa3be404274d06ca60e370eac7f13a89bac04dfa9b60e
(1) bc60af7de0563d369a644ca7c9a85f85c848d61b89bbb46fb9743f1deab776e0
(2) 5945ffbc2d5fe547ebf9c23dcdfae83e6954d962df05a8ed592df0a5f26fe578
(3) ffaf9bca756a42cc54cf6bb52e82bb9711255365cd6fd0f10293ae60bc08b0db
(4) f608a047b2fb964ac823bb1609823ee8e114922fa98914370585c052cd1f8b38
(5) 7d22b6be17763c8475fba12af464da2f780610f4c62c332d030ee8267d1e2ce8
(6) bb23d0cf5160f2ca3caf66d5ea026b32e0bd647771da5ad057370ca5de74d522
(7) 4b0a91b60b82f82968cb10f1f30a413fedab4a29f96e04cd08865f448c1710d1
(8) 725ab3a13f73b6e4dbeb9e32ba6e61a92116a4ff7bbb27f28fce7f2fe3783b27
(9) 1bd0cc4cf6c22efc114fdebbb526efe50bbe9ac278ae5596bf822d19b3c8d3ec

Mnemonic: poverty punch loan half parade photo document proof fetch outside shift wrist

⚠️  Important ⚠️  : This mnemonic was created for you by Truffle. It is not secure.
Ensure you do not use it on production blockchains, or else you risk losing funds.

truffle(develop)> 


truffle(develop)> migrate --reset

Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.


Starting migrations...
======================
> Network name:    'develop'
> Network id:      5777
> Block gas limit: 6721975 (0x6691b7)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x495166218a0f54a93498b36a118953bd416ab9a73f35639dedaf85aeb58b25e6
   > Blocks: 0            Seconds: 0
   > contract address:    0x300D6F5e2eDE9B3f30e15e7917f846A91B05e4B3
   > block number:        1
   > block timestamp:     1652000840
   > account:             0x49552CcC0Cb85c22208290B4710A46b09f997C40
   > balance:             99.99915573025
   > gas used:            250154 (0x3d12a)
   > gas price:           3.375 gwei
   > value sent:          0 ETH
   > total cost:          0.00084426975 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:       0.00084426975 ETH


2_deploy_contracts.js
=====================

   Deploying 'SimpleStorage'
   -------------------------
   > transaction hash:    0x6a3141b89a9748daa3722484b4db5504b02b9210aa5097b068d8b58dfa9beadd
   > Blocks: 0            Seconds: 0
   > contract address:    0xa8b26595e0c6925b3Cf1304E5B89ce9c134CCB07
   > block number:        3
   > block timestamp:     1652000842
   > account:             0x49552CcC0Cb85c22208290B4710A46b09f997C40
   > balance:             99.998606050600155647
   > gas used:            125653 (0x1ead5)
   > gas price:           3.178366198 gwei
   > value sent:          0 ETH
   > total cost:          0.000399371247877294 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:     0.000399371247877294 ETH

Summary
=======
> Total deployments:   2
> Final cost:          0.001243640997877294 ETH





https://testnet.binance.org/faucet-smart

Copy from above Acounts of (0): 0x49552ccc0cb85c22208290b4710a46b09f997c40









