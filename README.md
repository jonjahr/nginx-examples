## Why?

Basic NGINX servers to quickly get you up and running.

## What's included?

- Basic www domain
- Basic subdomain
- Basic wordpress site

## How do I use it?

- Copy server blocks from `/sites-available` to your server's `/etc/nginx/sites-available`.
- Remember to also copy `/snippets` to your server's `/etc/nginx/snippets`.

## Extras to consider:

- Add HTTPS with Certbot
- Protect against XSS and SQL Injection with [NAXSI nginx module](https://github.com/nbs-system/naxsi)

## NGINX Commands:

```
# Activate a site:
sudo ln -s thisFile ../sites-enabled/thisFile

# Test new config:
sudo nginx -t

# Restart with new config:
sudo systemctl restart nginx
```

## VI Commands:

```
# Delete current line:
dd

# Delete all lines:
%d
```

## NGINX's boilerplate introduction

You should look at the following URL's in order to grasp a solid understanding
of Nginx configuration files in order to fully unleash the power of Nginx.
http://wiki.nginx.org/Pitfalls
http://wiki.nginx.org/QuickStart
http://wiki.nginx.org/Configuration

Generally, you will want to move this file somewhere, and start with a clean
file but keep this around for reference. Or just disable in sites-enabled.
Please see /usr/share/doc/nginx-doc/examples/ for more detailed examples.
