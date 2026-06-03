# kaniko-images

Repository to build OCI images of kaniko forks.

Supports:

* [osscontainertools fork of kaniko](https://github.com/osscontainertools/kaniko)
* [chainguard-forks fork of kaniko](https://github.com/chainguard-forks/kaniko/)

Actions are taken from the original build process with few changes to adapt to ghcr and monkey patch version in `Makefile`.

To publish a new image, just run the "Build images" workflow with relevant inputs.

All credit here goes to @babs from where this project was forked: https://github.com/kaniko-build/builder
