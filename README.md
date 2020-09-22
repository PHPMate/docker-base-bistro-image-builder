# Base Bistro Docker image builder

Builder of base Docker image with Bistro.

[Bistro](https://bistro.io/) is:
> A toolkit for making services that schedule and execute tasks

___

### Github actions will do this:

- check if `bistro` directory exists
    - if NOT:
        - git clone https://github.com/facebook/bistro.git
- git checkout specific commit
- prepare Dockerfile context
- build docker image
- push image to registry
