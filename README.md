# CDN

Use CDN for caching and accelerating content loading around the world

# File compression

Compress files with gzip, brotli...

```js
//express
const compression = require('compression');
app.user(compresion());
```

```
# nginx
gzip on;
```

# Database scaling

Identify inefficient queries, use indexes when needed
Increase memory
Vertical scaling, use memory storage for caching (Redis, memcached)
Sharding
More databases, distribute the load
Database type (NoSql vs Sql, characteristics needed...)

# Caching

CDN, use memory storage, database caching

Use browser caching strategy via service worker, indexedDB
Use cache busting

# Load balancing

Use NGINX for example as a load balancer for serving our static files
NGINX, as the target of client request (Reverse proxy), will balance the load between our node servers





