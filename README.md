# contract-abi
This repo contains the abi file of the contract.

## generate abi
```
forge in src/Ledger.sol:Ledger abi > Ledger.json
forge in src/OperatorManager.sol:OperatorManager abi > OperatorManager.json
forge in src/Vault.sol:Vault abi > Vault.json
forge in src/VaultManager.sol:VaultManager abi > VaultManager.json
forge in src/FeeManager.sol:FeeManager abi > FeeManager.json
forge in src/MarketManager.sol:MarketManager abi > MarketManager.json
forge in src/testUSDC/tUSDC.sol:TestUSDC abi > TestUSDC.json
```

## contract address

### Vault address (Arb goerli L2)

TEST_USDC_ADDRESS="0x004d88aa993fd2100d6c8beb6cdb6bc04f565b44"
VAULT_ADDRESS="0x0C554dDb6a9010Ed1FD7e50d92559A06655dA482"

### Ledger address (OP Orderly L2)

OPERATOR_MANAGER_ADDRESS="0xe34614EB781C5838C78B7f913b89A05e7a5b97e2" // OPERATOR_MANAGER
VAULT_MANAGER_ADDRESS="0x4922872C26Befa37AdcA287fF68106013C82FeeD"
LEDGER_ADDRESS="0x8794E7260517B1766fc7b55cAfcd56e6bf08600e" // LEDGER
FEE_MANAGER_ADDRESS="0x835E970110E4a46BCA21A7551FEaA5F532F72701"
MARKET_MANAGER_ADDRESS="0x3ac2Ba11Ca2f9f109d50fb1a46d4C23fCadbbef6"