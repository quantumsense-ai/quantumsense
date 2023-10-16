# QuantumSense Website

QuantumSense website served by GitHub Pages.

## Description

This repository contains the QuantumSense website as a static website in the `docs/` directory.

> GitHub Pages can only serve from root or `docs/`, that's why the website directory is called `docs/`.

The website files in this repository are not intended to be edited manually. Instead, the website is developed as a WordPress website in the [quantumsense-ai/quantumsense-wordpress](https://github.com/quantumsense-ai/quantumsense-wordpress) repository.

From WordPress, the website is then exported as a static website with the [Simply Static](https://simplystatic.com/) WordPress plugin to this repository.

> Instructions for how to export the website from WordPress can be found in the [README](https://github.com/quantumsense-ai/quantumsense-wordpress#instructions) of the quantumsense-ai/quantumsense-wordpress repository. 

## Misc

The website in the `docs/` folder of this repository can be served locally as follows:

```bash
python3 -m http.server 8080
```
