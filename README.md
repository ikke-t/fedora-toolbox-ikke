# fedora-toolbox-ikke

My personal toolbox for fedora silverblue. Very initial one.

## Fedora 38

This has mostly the command line utils I had in my regular fedora.

build with:
```
buildah bud -t fedora-toolbox-ikke:38 Containerfile-f38
```

initiate with:

```
toolbox create --image localhost/fedora-toolbox-ikke:38 fedora-toolbox-38
```

