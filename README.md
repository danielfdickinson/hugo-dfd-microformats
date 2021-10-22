# DFD Hugo Microformats

A Hugo module for adding microformats to 'head' element

## Status

[![Netlify Status](https://api.netlify.com/api/v1/badges/aef567f3-91f6-46d1-ab62-c23e41b1625a/deploy-status)](https://app.netlify.com/sites/hugo-dfd-microformats/deploys)
## Demo Site

<https://hugo-dfd-microformats.wildtechgarden.ca>

## Features

TBD

## Basic Usage

### Importing the Module

1. The first step to making use of this module is to add it to your site or theme.  In your configuration file:

   ``config.toml``
   ```toml
   [module]
     [[module.imports]]
       path = "github.com/danielfdickinson/hugo-dfd-microformats"
   ```
   OR
   ``config.yaml``
   ```yaml
   module:
     imports:
       - path: github.com/danielfdickinson/hugo-dfd-microformats
   ```
2. Execute
   ```bash
   hugo mod get github.com/danielfdickinson/hugo-dfd-microformats
   hugo mod tidy
   ```
