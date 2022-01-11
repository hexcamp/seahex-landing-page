hexcamp-homepage
===

Website at https://hex.camp

## Paketo buildpack

### Building

```bash
pack build hex-camp-homepage --buildpack gcr.io/paketo-buildpacks/nginx
```

### Running

```bash
docker run --tty --env PORT=9090 --publish 9090:9090 hex-camp-homepage
```

### Viewing

```bash
curl -s localhost:9090
```

## License

MIT + Apache 2
