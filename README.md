# Docker doh-httpproxy

DOH httpproxy in Docker: https://pypi.org/project/doh-proxy/

```
docker run -d --name doh-httpproxy ghcr.io/olkitu/docker-doh-httproxy "--upstream-resolver 1.1.1.1 --level DEBUG"
```