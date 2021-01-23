# The Common Drone CI Configuration Templates

This project provides a common base of Drone CI's configuration file(.drone.yml) that should be easily adaptable for most project's with little modifications.

[![Continuous Integration(CI) status](https://cloud.drone.io/api/badges/Lin-Buo-Ren/common-drone-ci-configs/status.svg?github-camo-dont-cache=true)](https://cloud.drone.io/Lin-Buo-Ren/common-drone-ci-configs)

## How to use

1. Downlaod release archive from the [Releases](https://github.com/Lin-Buo-Ren/common-drone-ci-configs/releases) page
1. Extract the release archive
1. From the release folder, install the following files to your project's root directory
    - [.drone.yml](.drone.yml)  
      Drone CI configuration file
    - (Optional) [continuous-integration/](continuous-integration/)  
      Support files for convenience(CI, CD)
    - (Optional) [.gitattributes](.gitattributes)  
      Specify path patterns to exclude from the release archive
    - (Optional) [.pre-commit-config.yaml](.pre-commit-config.yaml)  
      [pre-commit](https://pre-commit.com) configuration file for continuous integration
    - (Optional) [.markdownlint.yml](.markdownlint.yml)  
      Markdownlint configuration file for checking Markdown documents

1. Profit!

## License

Unless otherwise specified, this template uses [the Creative Commons Attribution-ShareAlike License, version 4.0](https://creativecommons.org/licenses/by-sa/4.0), or any more recent version of your choice, with an exception of the license only covers the configuration file itself, but not other assets in your project.

For the attribution requirement, please retain the "This file is based on ..." mention and link to this project.
