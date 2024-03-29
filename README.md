# fedora-toolbox-ikke

My personal toolbox for Fedora Silverblue. The image is automatically built
at [Quay](https://quay.io/repository/ikke/fedora-toolbox-ikke/tag/latest).
Check Quay for [image security status](https://quay.io/repository/ikke/fedora-toolbox-ikke/tag/latest?tab=securityreport)

## Fedora 40

This has mostly the command line utils I had in my regular fedora.

build with:
```
buildah bud -t fedora-toolbox-ikke:40 Containerfile-f40
```

initiate with:

```
toolbox create --image localhost/fedora-toolbox-ikke:40 fedora-toolbox-40
```

