# 🦊 Foxo Browser

A Firefox-based browser project focused on customization, privacy and performance.

## Current Version
**Foxo Browser 0.2**

## About
Foxo Browser is a custom browser based on Mozilla Firefox.

This repository contains Foxo-specific source modifications and development documentation.

## Source Code
Foxo Browser 0.2 is based on Mozilla Firefox 160.0.

Original source code:
https://github.com/mozilla-firefox/firefox

Base version: `FIREFOX_160_0_RELEASE`

## Applying Foxo Changes

1. Download the Firefox 160 source code.
2. Extract the source archive.
3. Download `Foxo-0.2.patch` from this repository.
4. Apply the patch from the Firefox source directory:

```bash
git apply --ignore-space-at-eol Foxo-0.2.patch
