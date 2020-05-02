# cobol-buildpack

Cloud native buildpack for GnuCOBOL https://sourceforge.net/projects/open-cobol/

On Docker Hub [dashaun/cobol-buildpack](https://hub.docker.com/r/dashaun/cobol-buildpack)

## Version

Currently supports GnuCOBOL version 3.1-dev

## Getting Started

``` 
pack build <imagename> --path ./ --buildpack dashaun/cobol-buildpack
```

## Package the buildpack

``` 
$ pack package-buildpack dashaun/cobol-buildpack --package-config package/package.toml
Successfully created package dashaun/cobol-buildpack
$
```

## Publish the buildpack

``` 
$ pack package-buildpack dashaun/cobol-buildpack --package-config package/package.toml --publish
Successfully published package dashaun/cobol-buildpack
$
```

### Additional Resources

* [`pack create-builders` documentation](https://buildpacks.io/docs/using-pack/working-with-builders/)
* https://buildpacks.io/docs/buildpack-author-guide/create-buildpack/
* https://github.com/ayumin/heroku-buildpack-cobol
* https://open-cobol.sourceforge.io/