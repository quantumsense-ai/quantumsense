# QuantumSense Website

QuantumSense website served by GitHub Pages.

> ⚠️  Do not edit files in this repository manually. Use the [**quantumsense-wordpress**](https://github.com/quantumsense-ai/quantumsense-wordpress) repository instead, which is also where you can create issues for the website.

## Description

This repository contains the QuantumSense website as in the `docs` dirctory from where it is served by GitHub Pages.

> GitHub Pages can only serve from the root directory or from `docs`. That's why the website directory is called `docs`.

The website files in this repository are not intended to be edited manually. Instead, the website is developed with WordPress in the [**quantumsense-wordpress**](https://github.com/quantumsense-ai/quantumsense-wordpress) repository and from there the website is exported as a static website to this repository. 

The export of the website is done with the [Simply Static](https://simplystatic.com/) WordPress plugin. Instructions  can be found in the README of the [**quantumsense-wordpress**](https://github.com/quantumsense-ai/quantumsense-wordpress) repository.

## Misc

The website in the `docs` folder of this repository can be served locally as follows:

```bash
python3 -m http.server 8080
```
