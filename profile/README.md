# Hi Energy AI

**Affiliate marketing data, unified.** One API for deals, advertisers, commissions, and publisher analytics — built for developers and AI agents.

[![Website](https://img.shields.io/badge/website-hienergy.ai-0d6efd?style=for-the-badge)](https://www.hienergy.ai)
[![API Docs](https://img.shields.io/badge/API-documentation-0d6efd?style=for-the-badge)](https://app.hienergy.ai/api_documentation)
[![OpenAPI](https://img.shields.io/badge/OpenAPI-spec-0d6efd?style=for-the-badge)](https://app.hienergy.ai/api_documentation/openapi)

---

## What we build

[Hi Energy AI](https://www.hienergy.ai) aggregates and normalizes affiliate program data from major networks — **FlexOffers**, **CJ**, **Rakuten**, **Impact**, **Awin**, **Partnerize**, **Pepperjam**, **ShareASale**, and more — into a single **JSON API** with MCP and OpenAPI support.

| For | Use cases |
|-----|-----------|
| **Affiliate marketers** | Search deals and advertisers by domain, category, or keyword |
| **Publishers** | Track transactions, clicks, commissions, and status changes |
| **Developers** | Build dashboards, ETL pipelines, and internal tools |
| **AI agents** | MCP tools, structured pagination, and predictable schemas |

---

## Official SDKs

| Language | Package | Repository |
|----------|---------|------------|
| **Ruby** | [`hi_energy_ai`](https://rubygems.org/gems/hi_energy_ai) on RubyGems | [hi_energy_api](https://github.com/HiEnergyAgency/hi_energy_api) |
| **JavaScript / TypeScript** | [`hi-energy-ai`](https://www.npmjs.com/package/hi-energy-ai) on npm | [hi-energy-ai-js](https://github.com/HiEnergyAgency/hi-energy-ai-js) |

```ruby
# Ruby
client = HiEnergyAi.new(api_key: ENV["HI_ENERGY_API_KEY"])
client.deals.list(active: true, country: "US")
```

```typescript
// JavaScript / TypeScript
import { Client } from "hi-energy-ai";
const client = new Client({ apiKey: process.env.HI_ENERGY_API_KEY! });
await client.deals.list({ active: true, country: "US" });
```

**API base URL:** `https://app.hienergy.ai/api/v1` · **Auth:** `X-Api-Key` header · [Get an API key](https://app.hienergy.ai/api_documentation/api_key)

---

## Repositories

### API & clients

| Repo | Description |
|------|-------------|
| [hi_energy_api](https://github.com/HiEnergyAgency/hi_energy_api) | Official Ruby gem for the Hi Energy AI API |
| [hi-energy-ai-js](https://github.com/HiEnergyAgency/hi-energy-ai-js) | Official JavaScript/TypeScript SDK |

### AI integrations

| Repo | Description |
|------|-------------|
| [chatgpt_hienergy_skill](https://github.com/HiEnergyAgency/chatgpt_hienergy_skill) | ChatGPT skill for Hi Energy Rocket |
| [hienergy-gpt-action](https://github.com/HiEnergyAgency/hienergy-gpt-action) | GPT Actions integration |

---

## Quick links

- **Product:** [hienergy.ai](https://www.hienergy.ai)
- **App:** [app.hienergy.ai](https://app.hienergy.ai)
- **API documentation:** [app.hienergy.ai/api_documentation](https://app.hienergy.ai/api_documentation)
- **OpenAPI:** [app.hienergy.ai/api_documentation/openapi](https://app.hienergy.ai/api_documentation/openapi)
- **Staging API docs:** [staging.hienergyrocket.com/api_documentation](https://staging.hienergyrocket.com/api_documentation)

---

## Contact

Questions or partnership inquiries: [patrick@hienergyagency.com](mailto:patrick@hienergyagency.com)
