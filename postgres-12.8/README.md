Postgres images with plv8, built on top of official Postgres images.

### Building an image

```bash
docker build -t "postgres:12.8-plv8-2.3.15"

or you can change version args by --build-arg

docker build -t postgres:12.8-plv8-2.3.15 \
  --build-arg OFFICIAL_IMAGE_TAG="12.8" \
  --build-arg PLV8_VERSION="2.3.13" .
```



## References

* [plv8](https://plv8.github.io/)