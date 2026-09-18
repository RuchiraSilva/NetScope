# NetScope — Free Network Support Toolkit

**[Open NetScope →](https://ruchirasilva.github.io/NetScope/)**

NetScope is a free, browser-based toolkit for network and support engineers troubleshooting connectivity issues — no install, no signup, no backend. Everything runs client-side and is hosted free on GitHub Pages.

## Tools included

- **MAC Address / Vendor Lookup** — identify a device manufacturer from its MAC address (OUI lookup)
- **IP Address Lookup** — geolocation, network/ISP ownership, reverse DNS (PTR), and spam blacklist (DNSBL) status for any IPv4 or IPv6 address
- **DNS & WHOIS/RDAP Lookup** — query A/AAAA/MX/TXT/NS/CNAME/SOA/CAA records and pull domain registration data
- **BGP / ASN Lookup** — routing, network ownership, and abuse contact info via RIPEstat
- **HTTP Reachability & Latency Check** — test whether a URL is reachable and how long it takes to respond
- **Service Status ("Is it down?")** — live status for GitHub, Cloudflare, OpenAI, Slack, Dropbox, DigitalOcean, and more, plus reachability checks for everyday services like YouTube, Facebook, WhatsApp, Instagram, and Netflix

## Why NetScope

Most "is it down" or MAC/IP lookup tools require you to trust a third-party service with no visibility into how it works. NetScope is a single, open-source, static HTML file — inspect the code, fork it, self-host it, or run it locally with no build step.

## Hosting

NetScope is a single self-contained `index.html` file with no build step or dependencies. It's deployed via [GitHub Pages](https://pages.github.com/) directly from this repository.

## Local use

Clone the repo and open `index.html` in a browser, or serve it with any static file server.

## Tech

Plain HTML/CSS/JavaScript. Live data comes from free public APIs: DNS-over-HTTPS (Google & Cloudflare), RIPEstat, RDAP, ipapi.co/ipwho.is, and each service's own public status-page API.

## License

MIT
