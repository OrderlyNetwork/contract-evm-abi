# contract-abi

This repo contains the abi file of the contract.

## generate abi

```
forge in src/Ledger.sol:Ledger abi > Ledger.json
forge in src/OperatorManager.sol:OperatorManager abi > OperatorManager.json
forge in src/zip/OperatorManagerZip.sol:OperatorManagerZip abi > OperatorManagerZip.json
forge in src/vaultSide/Vault.sol:Vault abi > Vault.json
forge in src/VaultManager.sol:VaultManager abi > VaultManager.json
forge in src/FeeManager.sol:FeeManager abi > FeeManager.json
forge in src/MarketManager.sol:MarketManager abi > MarketManager.json
```
