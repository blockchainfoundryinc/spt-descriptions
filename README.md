# SPT Descriptions

This repository contains Syscoin Platform Token definitions for the Spark mobile wallet.

## Adding your SPT

1. Fork this repository.
2. Edit `spt.json` adding your tokens information as a new entry. The entry should follow the **SPT Definition Specification**.
3. Add your SPT image logo (PNG, JPG, or SVG) to the `logos` directory.
4. Submit a pull request back to the master branch of this repository.

## SPT Definition Specification 

Syscoin Platform Token definition entries should adhere to the following specification:

```
"SYS-1805583979": {
  "asset_guid": [token guid],
  "symbol": [token symbol],
  "name": [token name],
  "url": [URL of token project website],
  "logo": [remote URL to logo asset]
},
```
