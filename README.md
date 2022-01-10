# DFD Hugo Microformats

A Hugo module for adding microformats to 'head' element

## Status

ARCHIVED: This module has been archived and is merged into (and replaced by) <https://github.com/danielfdickinson/metadata-mod-hugo-dfd>.

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
