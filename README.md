# contract-abi
This repo contains the abi file of the contract.

## generate abi
```
forge in src/Ledger.sol:Ledger abi > Ledger.json
forge in src/OperatorManager.sol:OperatorManager abi > OperatorManager.json
forge in src/vaultSide/Vault.sol:Vault abi > Vault.json
forge in src/VaultManager.sol:VaultManager abi > VaultManager.json
forge in src/FeeManager.sol:FeeManager abi > FeeManager.json
forge in src/MarketManager.sol:MarketManager abi > MarketManager.json
forge in src/testUSDC/tUSDC.sol:TestUSDC abi > TestUSDC.json
```

## contract Address for Dev env

### Vault address (Arb goerli L2)

TEST_USDC_ADDRESS="0x004d88aa993fd2100d6c8beb6cdb6bc04f565b44"

VAULT_ADDRESS="0x0C554dDb6a9010Ed1FD7e50d92559A06655dA482"

### Ledger address (OP Orderly L2)

OPERATOR_MANAGER_ADDRESS="0xe34614EB781C5838C78B7f913b89A05e7a5b97e2" // OPERATOR_MANAGER

VAULT_MANAGER_ADDRESS="0x4922872C26Befa37AdcA287fF68106013C82FeeD"

LEDGER_ADDRESS="0x8794E7260517B1766fc7b55cAfcd56e6bf08600e" // LEDGER

FEE_MANAGER_ADDRESS="0x835E970110E4a46BCA21A7551FEaA5F532F72701"

MARKET_MANAGER_ADDRESS="0x3ac2Ba11Ca2f9f109d50fb1a46d4C23fCadbbef6"

## Contract Address for QA env

### Vault address (Arb goerli L2)

TEST_USDC_ADDRESS="0x6aad876244e7a1ad44ec4824ce813729e5b6c291"

VAULT_ADDRESS="0x22b10472d3Da206aaA85D3f19E91A8da15E0F56A"

### Ledger address (OP Orderly L2)

OPERATOR_MANAGER_ADDRESS="0x7Cd1FBdA284997Be499D3294C9a50352Dd682155"

VAULT_MANAGER_ADDRESS="0x3B092aEe40Cb99174E8C73eF90935F9F35943B22"

LEDGER_ADDRESS="0x50F59504D3623Ad99302835da367676d1f7E3D44"

FEE_MANAGER_ADDRESS="0x8A929891DE9a648B6A3D05d21362418f756cf728"

MARKET_MANAGER_ADDRESS="0x1AFE8286eD1b365671870A735f7deb4dcc9DB16D"

## Contract Address for Staging env

### Vault address (Arb goerli L2)

TEST_USDC_ADDRESS="0x6aad876244e7a1ad44ec4824ce813729e5b6c291"

VAULT_ADDRESS="0xd64AeB281f3E8cd70e668b6cb24De7e532dC214D"

### Ledger address (OP Orderly L2)

OPERATOR_MANAGER_ADDRESS=""

VAULT_MANAGER_ADDRESS=""

LEDGER_ADDRESS=""

FEE_MANAGER_ADDRESS=""

MARKET_MANAGER_ADDRESS=""


