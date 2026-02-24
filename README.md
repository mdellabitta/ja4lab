# JA4 Fingerprinting Lab

This repo is a toy setup using docker compose to be able to demonstrate how [JA4 browser fingerprinting](https://github.com/FoxIO-LLC/ja4) works to the audience for a [presentation](https://docs.google.com/presentation/d/e/2PACX-1vQZBdxVqihPOx-KAf1I-nhdiMAv6iu6R-PH-Yrye_OoafnDqMOfhjHVFh2WQ5gzsaXuK5O25Uq-bJxa/pub?start=false&loop=false&delayms=3000) I'm giving.

To use it, you'll need an environment that can run docker compose (I used Podman), and having the [mise](https://mise.jdx.dev/) tool will let you run some automated tasks (submodule setup and file munging, self-signed ssl cert creation). Just run `mise run` to see what the available commands are.
