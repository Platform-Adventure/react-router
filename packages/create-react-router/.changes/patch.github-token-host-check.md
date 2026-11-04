Only send the `--token` authorization header to `github.com` and its subdomains

- Previously, any host ending in `github.com` (such as `evilgithub.com`) would receive the token
