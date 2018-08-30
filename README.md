## Why?

Basic NGINX server blocks (and snippets) for your server.

## NGINX Intro

You should look at the following URL's in order to grasp a solid understanding
of Nginx configuration files in order to fully unleash the power of Nginx.
http://wiki.nginx.org/Pitfalls
http://wiki.nginx.org/QuickStart
http://wiki.nginx.org/Configuration

Generally, you will want to move this file somewhere, and start with a clean
file but keep this around for reference. Or just disable in sites-enabled.
Please see /usr/share/doc/nginx-doc/examples/ for more detailed examples.

## Useful NGINX Commands:

```
# Activate a site:
sudo ln -s thisFile ../sites-enabled/thisFile

# Test new config:
sudo nginx -t

# Restart with new config:
sudo systemctl restart nginx
```

## Vim Commands:

```
# Delete current line:
dd

# Delete all lines:
%d
```
