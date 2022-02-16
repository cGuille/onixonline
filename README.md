ONIX online
===========

I did not find an online, browsable version of the ONIX specification [on EDItEUR's website](https://www.editeur.org/8/ONIX/).
So I decided to download the specification in HTML version and host it here for anyone to browse easily.

This repository contains two subdirectories:

1. `build/` holds scripts to download, extract, and build the online version.
2. `docs/` the browsable files that are being served by GitHub pages.

To update the docs:

1. Find the archive's download URL [on the official website](https://www.editeur.org/93/Release-3.0-Downloads) (HTML in ZIP).
2. Update the download URL in [the configuration](build/config.bash).
3. Build the docs with the `build/run` script.
4. Commit and push the changes.
5. Wait for GitHub pages to publish the changes.
