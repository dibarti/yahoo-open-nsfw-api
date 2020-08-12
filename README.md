# yahoo-open-nsfw-http

HTTP service wrapper for [Yahoo Open NSFW model](https://github.com/yahoo/open_nsfw)

```bash
docker run -p 127.0.0.1:5000:5000 -d dibarti/yahoo-open-nsfw-http
```

```bash
curl -X POST 127.0.0.1:5000 --data-binary @path/to/image.jpg
```
