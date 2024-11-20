# firmware-action example

Example usage of [firmware-action](https://github.com/9elements/firmware-action).


## How to use

```bash
git clone --depth 1 git@github.com:9elements/firmware-action-example.git
cd firmware-action-example
git submodule update --depth 1 --init --recursive
firmware-action build --config=firmware-action.json --target=coreboot-example
```
