Source code for my website, [hyblan.com](https://hyblan.com/)

includes mirror
=======
Source code for my website, [hyblan.com](https://hyblan.com/).

## Mirroring configuration

The `Mirror develop -> hyblancode/hyblancode.github.io-develop:develop` workflow mirrors the `develop` branch into the `hyblancode.github.io-develop` repository. Set the repository variable `MIRROR_FORCE_OVERWRITE` to `true` to enable unconditional mirroring, which forces the target branch even when history diverges. When the variable is unset or `false`, the workflow uses a force-with-lease push for safer mirroring.

