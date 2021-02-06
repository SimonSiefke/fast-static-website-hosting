# Caching Headers

Best for immutable resources (js, css, images):

```
Cache-Control: public,max-age=31536000,immutable
```

Best for static content (blog site html, etc.):

```
Cache-Control: public,max-age=3600,immutable
```
