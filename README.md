# nf-plugin-sdk

This is an unofficial tool to install/uninstall Nextflow plugins

The idea of `nf-plugin-sdk` is to have a simple bash to install plugins from GitHub or
Maven using their coordinates, i.e.:

`./nf-plugin-sdk install github edn-es:nf-plugin-template:v0.0.8-rc1`

or

`./nf-plugin-sdk install maven es.edn:nf-plugin-template:0.0.8-rc1`

This bash will resolve the URL to the zip and download into the $HOME/.nextflow/plugin folder

## How to use

- Grab the bash

`curl -LO https://github.com/edn-es/nf-plugin-sdk/releases/download/0.0.1/nf-plugin-sdk`

- Allow execution

`chmod +x ./nf-plugin-sdk`

- Install a plugin directly from Github

`./nf-plugin-sdk install github edn-es:nf-parquet:v0.0.1-rc2`
