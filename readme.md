# ImageMagick for AWS Lambda (minified version)

Generate a Lambda Layer with ImageMagick and minimal libraries

| Content | Version |
| :-- | :-- |
| ImageMagick | 7.0.9-20 |
| libjpg | 9d |
| libpng | 1.6.37 |

### Build

```bash
# download the code
$ git clone \
    --depth 1 \
    https://github.com/jeromedecoster/imagemagick-lambda-layer.git \
    /tmp/aws

# cd and build
$ cd /tmp/aws && make
```

### Already built

Check the [releases](https://github.com/jeromedecoster/imagemagick-lambda-layer/releases)

### License & Thanks

This is mainly a rewrite of the excellent [imagemagick-aws-lambda-2](https://github.com/serverlesspub/imagemagick-aws-lambda-2)
