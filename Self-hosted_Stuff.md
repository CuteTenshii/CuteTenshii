# Self-hosted Stuff

Sometimes I self-host software on my VPS. Here's a complete list of all the software I self-host.

[VPS Specs](VPS_Specs.md)

## [Vaultwarden](https://vw.yuuto.dev)

[Vaultwarden](https://github.com/dani-garcia/vaultwarden) is a Bitwarden compatible server written in Rust.

## [Plausible](https://analytics.yuuto.dev)

[Plausible](https://plausible.io/) is a privacy-friendly analytics tool. It's fully compliant with the GDPR, the CCPA and the PECR. Also, it has a much better UI than Google Analytics.

[Yuuto.dev analytics](https://analytics.yuuto.dev/yuuto.dev/) (yes with Plausible you can make a website analytics public)

## Portainer

[Portainer](https://www.portainer.io/) is a way for me to manage my 20 containers. I really like Docker Compose, but it was starting to be a mess when the `docker-compose.yml` was 200+ fking lines.

## NPMPlus

[NPMplus](https://github.com/ZoeyVid/NPMplus) is a fork of [Nginx Proxy Manager](https://nginxproxymanager.com), which is a project that aims to manage Nginx directly from a web UI. This is very handsome because I don't have to edit Nginx configurations (and probably break everything 🥲)

In addition to this reverse proxy, I use [Cloudflare](https://www.cloudflare.com/), which allows me to have [HTTP/3](https://en.wikipedia.org/wiki/HTTP/3), [Early Hints](https://developer.mozilla.org/docs/Web/HTTP/Status/103), [their CDN](https://www.cloudflare.com/application-services/products/cdn/), [SSL certificates](https://www.cloudflare.com/application-services/products/ssl/) (NPM allows you to generate them but it's annoying to have to generate certificates for all the subdomains)...

## [Uptime Kuma](https://status.miwa.lol)

[Uptime Kuma](https://github.com/louislam/uptime-kuma) is a self-hosted monitoring tool that I use to monitor my website [Miwa.lol](https://miwa.lol) services (the website, the Discord bot, and CDN - which is just a Cloudflare R2 bucket).

## WireGuard

[WireGuard](https://www.wireguard.com/) is a fast & secure VPN tunnel. My VPS is located in the United States, so this allows me to *travel* to the United States (at least, my Internet and my IP).
