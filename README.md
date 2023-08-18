# contract-abi
This repo contains the abi file of the contract.

## generate abi
```
forge in src/Ledger.sol:Ledger abi > Ledger.json
forge in src/OperatorManager.sol:OperatorManager abi > OperatorManager.json
forge in src/Vault.sol:Vault abi > Vault.json
forge in src/testUSDC/tUSDC.sol:TestUSDC abi > TestUSDC.json
```

## contract address

### Vault address (Fuji)

TEST_USDC_ADDRESS="0x1826B75e2ef249173FC735149AE4B8e9ea10abff"

VAULT_ADDRESS="0x523Ab490B15803d6Ba60dC95F1579536F95edD4e"

### Ledger address (Orderly subnet)

OPERATOR_MANAGER_ADDRESS="0x7831C3587388bdC4b037E4F01C82Edd1d4edCA99"

VAULT_MANAGER_ADDRESS="0xEbA7BEf0AF268f60fA572B7FDa286f876Ad44BEb"

LEDGER_ADDRESS="0xB3b86341E796684A7D33Ca102703b85BDE5925b6"

FEE_MANAGER_ADDRESS="0x3bF7fbf5B61DEFC9ee26972AfB1a4A4977b6A2fd"

MARKET_MANAGER_ADDRESS="0x21759c38A7047d73Fe77db5693f12Dc4F51f81Ff"