<a id="readme-top"></a>

<div align="center">

[![Contributors](https://img.shields.io/github/contributors/cinepro-org/core?style=for-the-badge&color=green)](#top-contributors)
[![Forks](https://img.shields.io/github/forks/cinepro-org/core?style=for-the-badge&color=blue)](https://github.com/cinepro-org/core/forks)
[![Stars](https://img.shields.io/github/stars/cinepro-org/core?style=for-the-badge&color=gold)](https://github.com/cinepro-org/core/stargazers)
[![GitHub License](https://img.shields.io/badge/license-PolyForm-orange?style=for-the-badge)
](LICENSE)

# CinePro Core 🎬

### _Support CinePro's Development by starring this repo!_ ⭐

<img src="https://repository-images.githubusercontent.com/1138947882/af901757-a06b-442d-8976-c485fcafc230"></img>

#### OMSS-compliant streaming backend powering the CinePro ecosystem.
Built with [@omss/framework](https://www.npmjs.com/package/@omss/framework) for extensible, type-safe media scraping.

**[📖 Documentation](https://docs.cinepro.cc)** · **[💬 Discussions](https://github.com/orgs/cinepro-org/discussions)** · **[🐛 Issues](https://github.com/cinepro-org/core/issues)**

</div>

---

CinePro Core is the central scraping and streaming engine of the CinePro ecosystem. It exposes an [OMSS-compliant](https://github.com/omss-spec/omss-spec) HTTP API for resolving movie and TV show stream sources from multiple providers, with Redis caching and full Docker support. Now even with MCP support for your AI agents! (The first streaming server worldwide to offer this feature). **Get up to 50+ unique sources for a single movie/tv show!**

> [!CAUTION]
> CinePro Core is designed for **personal and home use only.**  
> While we do not stop you from hosting it publicly, it ~might be~ is insecure by default!*
> Users are responsible for ensuring compliance with applicable laws and the terms of service of streaming sources.

<details><summary>*:</summary>
CinePro/core is a scraper. Meaning it "clicks through" shady websites to get the actual streaming link and gives them to you, bypassing the whole ad/scam stuff. However, since this process takes up computing power this is also a vulnerable to (D)DOS attacks, which (if you deploy it online) can shoot your costs over the moon.
We highly recommend you running it locally. Stay tuned for an easier documentation how to actually use it as an end user.
</details>

## Quick Start

**Prerequisites:** Node.js 20+, a [TMDB API key](https://www.themoviedb.org/settings/api)

```bash
git clone https://github.com/cinepro-org/core.git && cd core
npm install
cp .env.example .env   # add your TMDB_API_KEY and configure more options if you want
npm run dev            # http://localhost:3000
```

For Docker, production setup, and full configuration options → **[Quickstart](https://docs.cinepro.cc/quickstart)**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Features

- 🎯 **OMSS-Compliant** – follows the Open Media Streaming Standard
- 🔌 **Modular Providers** – drop-in provider system with auto-discovery
- 🛡️ **Type-Safe** – full TypeScript with strict mode
- ⚡ **Production-Ready** – Redis caching, Docker, error handling
- 🎬 **Multi-Source** – movies and TV shows from multiple providers
- 📺 **Stremio Compatibility** - with the `STREMIO_ADDON` env variable you can enable a stremio addon at `/stremio/manifest.json` which you can add to your stremio client
- (roadmap end of 2026) 📦 **CineHome Integration** – works with CineHome download automation

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Documentation

Full docs, API reference, configuration guide, and provider development at **[the CinePro Docs](https://docs.cinepro.cc)**.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

PRs are welcome — especially new providers, bug fixes, and docs improvements.  
See the [Documentation](https://docs.cinepro.cc/core/general-information/development) and the [Contributing Guideline](https://github.com/cinepro-org/core?tab=contributing-ov-file#contributing-to-cinepro-core) for details.

### Top contributors:

<a href="https://github.com/cinepro-org/core/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=cinepro-org/core" alt="contrib.rocks image" />
</a>

*Join now by contributing!*

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Graphs

![Repobeats analytics image](https://repobeats.axiom.co/api/embed/94fe2818e3f3254c91180779917073d3dbb1ace1.svg "Repobeats analytics image")

<a href="https://www.star-history.com/#cinepro-org/core&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=cinepro-org/core&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=cinepro-org/core&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=cinepro-org/core&type=date&legend=top-left" />
 </picture>
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

PolyForm Noncommercial License 1.0.0 © CinePro Organization — see [LICENSE](LICENSE) for details.  
This software does not host, store, or distribute any copyrighted content.
ANY DMCA Complaints should be opened at the hosting provider and not directed at us.
[Read more here](https://docs.cinepro.cc/core/general-information/license)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
