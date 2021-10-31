# free-proxy-list

Free Proxy API powered by [ProxyDig.com](https://proxydig.com/)

## Curl

```curl
curl --request GET 'https://proxydig.com/api/proxies/?apikey='
```

## Python

```python
import requests
resp = requests.get('https://proxydig.com/api/proxies/?apikey=')
proxies = resp.json()
```
