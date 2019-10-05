# Felicitas Pojtinger's KubeVirt Images Generator

[Forked from `Tedezed`](https://github.com/Tedezed/kubevirt-images-generator)

## Features

- Generate KubeVirt disk images from `img`, `iso`, `qcow2`, `tar`, `gz` or `xz` images

## Usage

```
# Set the user data (optional)
edit data/user-data
# Set the registry (required)
source data/variables.sh
# Then build and push the images
./src/generator.sh
```

## License

SPDX-License-Identifier: AGPL-3.0
