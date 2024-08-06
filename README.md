# golem-scripts
scripts to test mining CREATE3 salts on golem.network

## Getting Started
install dependencies
```bash
yarn
```

start yagna
```bash
yagna service run
```

## Running 
run the cpu image
```bash
node src/cpu.mjs <leading|pattern> <args> <deployer_address> 
```

## Examples 
run the cpu image with 4 leading zero bytes (8 zeros)
```bash
node src/cpu.mjs leading 4 0x4206a72a50231424043fff5cea705e41b6e6b09b

```
run the cpu image with starting with 0x1234
```bash
node src/cpu.mjs pattern 1234XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX 0x4206a72a50231424043fff5cea705e41b6e6b09b
```

