# defi-yeild-farming-brownie

## Installation

```sh
pip install --user pipx
pipx ensurepath
# restart your terminal
pipx install eth-brownie
```

## Running the script
deploy contract
```sh
brownie run scripts/deploy --network kovan
```

## Running the test
test development
```sh
brownie test
```
kovan testnet
```sh
brownie test --network kovan
```