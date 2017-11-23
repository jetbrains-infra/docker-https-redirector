# docker-https-redirector
HTTPS redirector, based on [SergeyZh/docker-https-redirector|https://github.com/SergeyZh/docker-https-redirector]

There are enviromental variables to set:
* SERVER_NAME (default is '_')
* REDIRECT_HOST (default is '$host')

Example:
```
docker run -e "REDIRECT_HOST=www.jetbrains.com" -p 80:80 jetbrainsinfra/https-redirector
```