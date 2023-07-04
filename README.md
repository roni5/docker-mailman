# library images on steroids for library/maxking
## Wrapped images
- [docker-images](https://github.com/corpusops/docker-images) compatibles images (original images wrapped with tools)
- [![.github/workflows/cicd.yml](https://github.com/corpusops/docker-maxking/workflows/.github/workflows/cicd.yml/badge.svg?branch=main)](https://github.com/corpusops/docker-maxking/actions?query=workflow%3A.github%2Fworkflows%2Fcicd.yml+branch%3Amain)
- for
    - workarounding hyperkitty not upgraded to 1.2.0 see https://github.com/maxking/docker-mailman/pull/528/files
    - add cron & logrotate

| original   | wrapped  |
|------------|-----------|
| [maxking/mailman-core](https://hub.docker.com/r/maxking/mailman-core)([./maxking/mailman-core](./maxking/mailman-core))                             | [corpusops/maxking-mailman-core](https://hub.docker.com/r/corpusops/maxking-mailman-core)                 |
| [maxking/mailman-web](https://hub.docker.com/r/maxking/mailman-web)([./maxking/mailman-web](./maxking/mailman-web))                             | [corpusops/maxking-mailman-web](https://hub.docker.com/r/corpusops/maxking-mailman-web)                 |
