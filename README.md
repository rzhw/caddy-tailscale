# Custom Caddy containers

This repository builds Docker containers for Caddy with certain plugins included
for convenience purposes.

It was created by forking [caddy-tailscale](https://github.com/tailscale/caddy-tailscale),
as I felt its Dockerfile provided a good base.

## Variants

- caddy-tailscale: Functionally equivalent to [caddy-tailscale](https://github.com/tailscale/caddy-tailscale),
  but dependencies may be built at different versions as this repo's go.mod and go.sum are managed separately.
- caddy-l4-tailscale: Includes both the [caddy-l4](https://github.com/mholt/caddy-l4) app and
  [caddy-tailscale](https://github.com/tailscale/caddy-tailscale) plugin.
