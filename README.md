# Docker doh-httpproxy

```Upstream project is not anymore maintained so I will archive this project too```

DOH httpproxy in Docker: https://pypi.org/project/doh-proxy/

```
docker run --name doh-httpproxy -p 8080:8080 -d ghcr.io/olkitu/docker-doh-httpproxy:main \
    --upstream-resolver 1.1.1.1 \
    --level DEBUG
```

## License

[MIT](https://github.com/olkitu/docker-doh-httpproxy/blob/main/LICENSE)
