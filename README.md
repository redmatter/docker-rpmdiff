# docker-rpmdiff

Docker image for comparison of RPMs using [pkgdiff](https://lvc.github.io/pkgdiff).

## Usage

Run directly from the commandline:

```
docker run -v ${PWD}:/workspace --rm redmatter/rpmdiff package-0.0.1.rpm package-0.0.2.rpm
```

