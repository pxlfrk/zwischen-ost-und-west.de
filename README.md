# zwischen-ost-und-west.de

[![hugo-CI zwischen-ost-und-west.de](https://github.com/pxlfrk/zwischen-ost-und-west.de/actions/workflows/hugo-CI.yml/badge.svg)](https://github.com/pxlfrk/zwischen-ost-und-west.de/actions/workflows/hugo-CI.yml)

Source code for static blog zwischen-ost-und-west.de

## Local development

### Clone repository including submodules

Run `git clone --recursive https://github.com/pxlfrk/blakoe.de` to clone the repository including its submodules.
In case you already ran git without `--recursive`, you can alternatively run `git submodule update --init --recursive` additionally when inside the repository's root folder (see also [Sample Configuration Method 2](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation#sample-configyml)).

### Install Hugo

Make sure you have installed the latest Hugo version (`>=0.82.0`). In case `apt install hugo` only installs and old version, download the latest binary for your OS from [Hugo's Github repository](https://github.com/gohugoio/hugo/releases/latest) (on WSL, use the `_Linux-64bit.deb` variant) and install it (on WSL, do `apt install ./hugo_x.y.z_Linux-64bit.deb`).
Run `hugo version` to verify your installed version.

### Serve page locally

cd into site directory, then run `hugo serve --disableFastRender --buildDrafts`

## Create new post

Run `hugo new posts/<postname>.md` to create a new post based on the posts-template specified in `archetypes/posts.md`.

## Enable draft rendering

Edit `config.yml` and set `buildDrafts` to `true` or add the flag `--buildDrafts` when serving locally.
