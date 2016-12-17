# sgminer-optimal-configurations

Optimal configurations for [sgminer-gm](https://github.com/genesismining/sgminer-gm), organized by cryptocurrency and GPU architecture.

All hashrates are from [Ubuntu 16.04](https://www.ubuntu.com/download/server) using [amdgpu-pro 16.50](https://support.amd.com/en-us/kb-articles/Pages/AMDGPU-PRO-Install.aspx) and [AMD APP SDK v3.0](http://developer.amd.com/tools-and-sdks/opencl-zone/amd-accelerated-parallel-processing-app-sdk/). YMMV.

## Available Configurations

### XMR

| Vendor | GPU     | Hashrate |
|--------|---------|----------|
| AMD    | R9 380X | 555 h/s  |
| AMD    | R9 390  | 635 h/s  |
| AMD    | R9 390X | 725 h/s  |

## Basic Usage

```
cd sgminer-gm
git clone https://github.com/jramos/sgminer-optimal-configurations.git conf
./sgminer-gm -c conf/xmr/r9_380x.conf
```

## Contributing

Open an issue or pull request with your configuration and hardware details.

## Donating

```
BTC: 1FzEfbfgdxMH1oLpgz19refMUke2GhiJsU
XMR: 4A7RTRaTKAdhLGHXN8rBXPQa39a2psd5EYKwRpinAfSN1XPJZG3EfifDmXECJdRYwCVkKV84aRdGUZrfVEuvYuvfSLxoSgP
```

## Etc.

Released under the [MIT License](LICENSE). Use at your own risk.