# firmware-action example

Example usage of [firmware-action](https://github.com/9elements/firmware-action).


## How to use

Firstly, install `firmware-action` as [described in documentation](https://9elements.github.io/firmware-action/firmware-action/get_started/04_get_firmware_action.html).

Optionally, install [Taskfile](https://taskfile.dev/installation/). `Taskfile` in the examples below.

### Simple example

If running ArchLinux replace `task` with `go-task`.
```bash
git clone --depth 1 git@github.com:9elements/firmware-action-example.git
cd firmware-action-example
git submodule update --depth 1 --init --recursive
task build:coreboot
```

### Complex example

If running ArchLinux replace `task` with `go-task`.
```bash
git clone --depth 1 git@github.com:9elements/firmware-action-example.git
cd firmware-action-example
git submodule update --depth 1 --init --recursive
task build:coreboot-linuxboot:recursive
```
