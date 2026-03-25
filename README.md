# Awesome Free APIs 2026 🔥

> **300+ APIs that are completely free** — no API key, no signup, no credit card. Just send a request.

Stop paying for data. These APIs give you everything from weather to AI to security — for free.

⭐ **Star this repo** — new APIs added weekly.

---

## No API Key Required

### Data & Search
| API | Description | Example |
|-----|-------------|---------|
| [Wikipedia](https://en.wikipedia.org/api/rest_v1/) | Any article as JSON | `curl https://en.wikipedia.org/api/rest_v1/page/summary/Python` |
| [crt.sh](https://crt.sh) | SSL certificates, subdomain discovery | `curl "https://crt.sh/?q=%.github.com&output=json"` |
| [Archive.org](https://archive.org/developers/) | Wayback Machine, book metadata | `curl "https://archive.org/wayback/available?url=example.com"` |
| [Open Library](https://openlibrary.org/developers/api) | 20M+ books metadata | `curl "https://openlibrary.org/search.json?q=python"` |
| [DuckDuckGo](https://api.duckduckgo.com/) | Instant answers | `curl "https://api.duckduckgo.com/?q=python&format=json"` |

### Science & Research
| API | Description | Example |
|-----|-------------|---------|
| [arXiv](https://arxiv.org/help/api) | 2M+ research papers | `curl "http://export.arxiv.org/api/query?search_query=all:ai"` |
| [Crossref](https://api.crossref.org) | 130M+ papers, DOI lookup | `curl "https://api.crossref.org/works?query=machine+learning"` |
| [OpenAlex](https://openalex.org) | 250M+ research works | `curl "https://api.openalex.org/works?search=web+scraping"` |
| [PubMed](https://eutils.ncbi.nlm.nih.gov/) | 36M+ medical papers | `curl "https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esearch.fcgi?db=pubmed&term=ai"` |
| [NASA](https://api.nasa.gov) | Mars photos, asteroids, APOD | `curl "https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY"` |

### Security & OSINT
| API | Description | Example |
|-----|-------------|---------|
| [crt.sh](https://crt.sh) | Certificate transparency, subdomains | No key needed |
| [URLhaus](https://urlhaus-api.abuse.ch/) | Malicious URL database | `curl -d "url=http://example.com" https://urlhaus-api.abuse.ch/v1/url/` |
| [EmailRep.io](https://emailrep.io/) | Email reputation scoring | `curl "https://emailrep.io/test@example.com"` |
| [RDAP](https://rdap.org/) | Modern WHOIS replacement (JSON) | `curl "https://rdap.org/domain/example.com"` |
| [AbuseIPDB](https://www.abuseipdb.com/api) | IP reputation (free key) | 1,000 checks/day |
| [Shodan](https://developer.shodan.io/) | Device search (free key) | 100 results/search |
| [VirusTotal](https://developers.virustotal.com/) | File/URL scanning (free key) | 4 req/min |
| [HIBP](https://haveibeenpwned.com/API/) | Data breach checking | Free for individual lookups |
| [NVD](https://nvd.nist.gov/developers/) | 250K+ CVE vulnerability database | 5 req/30s (free key: 50) |
| [Censys](https://search.censys.io/api) | Internet host & certificate search | 250 queries/month free |
| [SecurityTrails](https://securitytrails.com/corp/api) | DNS history & subdomains | 50 queries/month free |
| [MalwareBazaar](https://bazaar.abuse.ch/api/) | Malware sample database | No key needed |

### Developer Tools
| API | Description | Example |
|-----|-------------|---------|
| [GitHub](https://api.github.com) | Repos, users, code search | `curl "https://api.github.com/search/repositories?q=web+scraping"` |
| [npm Registry](https://registry.npmjs.org) | Package metadata, downloads | `curl "https://registry.npmjs.org/express"` |
| [PyPI](https://pypi.org/simple/) | Python package metadata | `curl "https://pypi.org/pypi/requests/json"` |
| [cdnjs](https://cdnjs.com/api) | JS library CDN links | `curl "https://api.cdnjs.com/libraries?search=react"` |
| [Hacker News](https://hacker-news.firebaseio.com/) | Stories, comments, users | `curl "https://hacker-news.firebaseio.com/v0/topstories.json"` |
| [npms.io](https://api.npms.io/) | npm package quality scores | `curl "https://api.npms.io/v2/package/express"` |
| [Libraries.io](https://libraries.io/api) | Package dependency tracking (free key) | 60 req/min |

### Finance & Crypto
| API | Description | Example |
|-----|-------------|---------|
| [CoinGecko](https://www.coingecko.com/en/api) | Crypto prices, market cap | `curl "https://api.coingecko.com/api/v3/simple/price?ids=bitcoin&vs_currencies=usd"` |
| [Exchange Rates](https://open.er-api.com/) | Currency exchange rates | `curl "https://open.er-api.com/v6/latest/USD"` |

### Weather & Geo
| API | Description | Example |
|-----|-------------|---------|
| [Open-Meteo](https://open-meteo.com/) | Weather forecast, no key | `curl "https://api.open-meteo.com/v1/forecast?latitude=52.52&longitude=13.41&current_weather=true"` |
| [ip-api](http://ip-api.com/) | IP geolocation | `curl "http://ip-api.com/json/8.8.8.8"` |
| [CountryIs](https://country.is/) | IP to country | `curl "https://api.country.is/8.8.8.8"` |

### Media
| API | Description | Example |
|-----|-------------|---------|
| [Lorem Picsum](https://picsum.photos/) | Random images | `https://picsum.photos/200/300` |
| [Dog API](https://dog.ceo/dog-api/) | Random dog photos | `curl "https://dog.ceo/api/breeds/image/random"` |
| [Unsplash Source](https://source.unsplash.com/) | Free stock photos | Direct URL |

### Fun & Misc
| API | Description | Example |
|-----|-------------|---------|
| [Chuck Norris](https://api.chucknorris.io/) | Random jokes | `curl "https://api.chucknorris.io/jokes/random"` |
| [Cat Facts](https://catfact.ninja/) | Random cat facts | `curl "https://catfact.ninja/fact"` |
| [Bored API](https://www.boredapi.com/) | Activity suggestions | `curl "https://www.boredapi.com/api/activity"` |

---

## APIs That Need a Free Key

These require signup but the free tier is generous:

| API | Free Tier | What You Get |
|-----|-----------|-------------|
| Shodan | 100 results/search | Internet device search |
| VirusTotal | 4 req/min | Malware scanning |
| HIBP | 10 req/min | Breach checking |
| News API | 100 req/day | News headlines |
| OpenWeatherMap | 60 req/min | Weather data |
| Abstract API | 100 req/day | Email validation, IP |
| Cloudflare Radar | 10K req/day | Internet traffic data by country, top domains, attack trends |
| Geekbench Browser | No key needed | CPU benchmark scores for any processor |
| EmailRep | 20 req/day | Email reputation scoring |
| RDAP (IANA) | Unlimited | Domain/IP registration data (replacing WHOIS) |
| PyPI JSON API | No key needed | Python package metadata and versions |
| npm Registry | No key needed | npm package info and security advisories |

## Related
- [Reddit Data Toolkit](https://github.com/spinov001-art/reddit-data-toolkit) — Extract Reddit data without API key: posts, comments, scores, sentiment

- [Awesome Web Scraping 2026](https://github.com/spinov001-art/awesome-web-scraping-2026) — 77+ scraping tools
- [API Scraping Templates](https://github.com/spinov001-art/api-scraping-templates) — 20+ ready Python templates
- [Python Security Tools](https://github.com/spinov001-art/python-security-tools) — 10 security recon scripts
- [Free Developer Tools](https://github.com/spinov001-art/free-developer-tools-2026) — 200+ free dev tools
- [HN API Toolkit](https://github.com/spinov001-art/hn-api-toolkit) — Hacker News API scripts
- [Email OSINT Toolkit](https://github.com/spinov001-art/email-osint-toolkit) — Email reputation & breach tools
- [WHOIS Lookup Tools](https://github.com/spinov001-art/whois-lookup-tools) — Domain intelligence
- [npm Security Scanner](https://github.com/spinov001-art/npm-security-scanner) — npm vulnerability scanning
- [API Monetization Guide](https://github.com/spinov001-art/api-monetization-guide) — How to make money with APIs
- [Get Paid Writing Technical Articles](https://github.com/spinov001-art/get-paid-writing-technical-articles) — 25+ companies paying $200-1500/article
- [API Rate Limiter Patterns](https://github.com/spinov001-art/api-rate-limiter-patterns) — Token bucket, backoff, sliding window
- [ARM CPU Benchmarks](https://github.com/spinov001-art/arm-cpu-benchmarks) — ARM vs x86 performance comparisons
- [NVD Vulnerability Scanner](https://github.com/spinov001-art/nvd-vulnerability-scanner) — Scan Python deps against 250K+ CVEs
- [VirusTotal Scanner](https://github.com/spinov001-art/virustotal-scanner) — Scan files/URLs against 70+ AV engines
- [Shodan Scanner](https://github.com/spinov001-art/shodan-scanner) — Internet-connected device search
- [HIBP Password Checker](https://github.com/spinov001-art/hibp-password-checker) — Check passwords against 14B+ breaches
- [Censys Scanner](https://github.com/spinov001-art/censys-scanner) — Host & certificate search
- [Wine Linux Compatibility](https://github.com/spinov001-art/wine-linux-compatibility) — Run Windows apps on Linux

## Need Custom API Integration?

I build data pipelines that pull from any API. **[Hire me →](https://spinov001-art.github.io)**

---

**Know an API I missed?** [Open an issue](https://github.com/spinov001-art/awesome-free-apis-2026/issues) — I'll add it.
