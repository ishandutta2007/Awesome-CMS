# 🚀 Awesome-CMS

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome CMS Banner">
</p>

**Headless CMS** platforms provide content modeling, editorial interfaces, and APIs (REST/GraphQL) while leaving the frontend completely free. Popular commercial tools include Contentful, Sanity, Storyblok, Strapi Cloud, Prismic, Hygraph, ButterCMS, DatoCMS, Agility CMS, and Magnolia.

Below is a **curated list** of notable platforms and their open-source equivalents. The focus is on **open-source** solutions that can be self-hosted for full data ownership and zero licensing fees.

## 🏢 SaaS / Hosted Platforms

| SaaS Product | Description | Pricing & Free Tier | Company Size |
| :--- | :--- | :--- | :--- |
| **[Contentful](https://www.contentful.com/)** | Enterprise-grade headless CMS with strong content modeling, governance, localization, and a large marketplace. | Usage + seat based. Free tier: 5 users, 1 space, 2M API requests/mo. | ~$3 Billion Valuation |
| **[Sanity](https://www.sanity.io/)** | Real-time, developer-first content platform with highly flexible schemas (GROQ), collaborative Studio, and excellent customization. | Per-seat plans. Free tier: 3 users, 10GB bandwidth, 100k API requests/mo. | ~$500 Million Valuation |
| **[Storyblok](https://www.storyblok.com/)** | Visual editor focused headless CMS popular with marketers. Component-based content and live preview. | Seat-based. Free tier: 1 user, 250GB bandwidth, limited components. | ~$300 Million Valuation |
| **[Strapi Cloud](https://strapi.io/cloud)** | Managed hosting for the open-source Strapi CMS. Convenient when you want Strapi without running infrastructure. | Subscription. No free tier (Self-host is free). | ~$200 Million Valuation |
| **[Prismic](https://prismic.io/)** | Slice-based page building with a polished visual editor and strong Next.js / React integration. | Usage based. Free tier: 1 user, unlimited API calls. | ~$150 Million Valuation |
| **[Hygraph](https://hygraph.com/)** | GraphQL-native content platform with content federation capabilities. Strong for complex, multi-source content architectures. | Usage based. Free tier: 3 users, 1 project, 1M API operations/mo. | ~$100 Million Valuation |
| **[Magnolia](https://www.magnolia-cms.com/)** | Enterprise digital experience platform with both traditional and headless capabilities, strong in larger organizations. | Enterprise pricing. No free tier. | ~$50 Million Revenue |
| **[ButterCMS](https://buttercms.com/)** | Simple headless CMS with blog and page management APIs, aimed at developers who want quick integration. | Starts at $99/mo. No free tier. | ~$40 Million Valuation |
| **[DatoCMS](https://www.datocms.com/)** | Clean, developer-friendly headless CMS with excellent GraphQL support and a modern editorial experience. | Usage based. Free tier: 3 users, 1 project, 100k API requests/mo. | ~$30 Million Valuation |
| **[Agility CMS](https://agilitycms.com/)** | Headless CMS focused on structured content and digital experience management with REST + GraphQL APIs. | Usage based. Free tier: 1 user, 2,500 items. | ~$20 Million Valuation |

## 🔓 Open-Source Software

### 🥇 Leading Self-Hosted Headless CMS
- **[Strapi](https://github.com/strapi/strapi)** [![Stars](https://img.shields.io/github/stars/strapi/strapi?style=social&color=white)](https://github.com/strapi/strapi/stargazers) — The leading open-source headless CMS. 100% JavaScript/TypeScript, auto-generated REST & GraphQL APIs, customizable admin panel, plugins, i18n, and media library. MIT license. Extremely popular (~70k+ stars).
- **[Directus](https://github.com/directus/directus)** [![Stars](https://img.shields.io/github/stars/directus/directus?style=social&color=white)](https://github.com/directus/directus/stargazers) — Instantly turns any SQL database into a headless CMS + admin app with REST, GraphQL, and realtime APIs. Excellent for existing databases or data-heavy projects. Source-available (check current license terms).
- **[Payload CMS](https://github.com/payloadcms/payload)** [![Stars](https://img.shields.io/github/stars/payloadcms/payload?style=social&color=white)](https://github.com/payloadcms/payload/stargazers) — TypeScript-first, code-defined schemas. Can run as a full Next.js backend (Local API) or classic headless CMS. Auth, access control, and admin UI generated from config. MIT license. Rapidly growing favorite for modern stacks.

### 🐙 Git-Based / Static-Friendly
- **[Decap CMS](https://github.com/decaporg/decap-cms)** [![Stars](https://img.shields.io/github/stars/decaporg/decap-cms?style=social&color=white)](https://github.com/decaporg/decap-cms/stargazers) (formerly Netlify CMS) — Git-backed CMS that stores content as Markdown/YAML/JSON in your repository. Perfect for Jamstack and static sites. Completely free and open source.
- **[TinaCMS](https://github.com/tinacms/tinacms)** [![Stars](https://img.shields.io/github/stars/tinacms/tinacms?style=social&color=white)](https://github.com/tinacms/tinacms/stargazers) — Open-source Git-backed CMS with visual editing for React / Next.js / Astro sites. Content lives in the repo; real-time preview available.
- **[Sveltia CMS](https://github.com/sveltia/sveltia-cms)** [![Stars](https://img.shields.io/github/stars/sveltia/sveltia-cms?style=social&color=white)](https://github.com/sveltia/sveltia-cms/stargazers) — Modern, fast rewrite of Decap/Netlify CMS. Git-based, framework-agnostic, excellent i18n, and improved UX.

### 🛠️ Developer Frameworks & Other Strong Options
- **[Ghost](https://github.com/TryGhost/Ghost)** [![Stars](https://img.shields.io/github/stars/TryGhost/Ghost?style=social&color=white)](https://github.com/TryGhost/Ghost/stargazers) — Beautiful open-source publishing platform with a powerful Content API. Excellent as a headless CMS for blogs, newsletters, and memberships. MIT license.
- **[Wagtail](https://github.com/wagtail/wagtail)** [![Stars](https://img.shields.io/github/stars/wagtail/wagtail?style=social&color=white)](https://github.com/wagtail/wagtail/stargazers) — Django-based CMS with strong editorial features and headless API support. Popular in larger organizations and government sites.
- **[KeystoneJS](https://github.com/keystonejs/keystone)** [![Stars](https://img.shields.io/github/stars/keystonejs/keystone?style=social&color=white)](https://github.com/keystonejs/keystone/stargazers) — Highly flexible Node.js CMS/framework. Define schemas in code, get GraphQL API + Admin UI. Great for custom applications that need CMS capabilities.
- **[ApostropheCMS](https://github.com/apostrophecms/apostrophe)** [![Stars](https://img.shields.io/github/stars/apostrophecms/apostrophe?style=social&color=white)](https://github.com/apostrophecms/apostrophe/stargazers) — In-context editing focused open-source CMS built on Node.js. Good for teams that want visual editing while staying open source.

### 📌 Notable Mentions
- **[Statamic](https://github.com/statamic/cms)** [![Stars](https://img.shields.io/github/stars/statamic/cms?style=social&color=white)](https://github.com/statamic/cms/stargazers) — Flat-file / Laravel-based CMS (source-available core with commercial licenses for some features). Excellent developer experience.
- **[Plone](https://github.com/plone/plone)** [![Stars](https://img.shields.io/github/stars/plone/plone?style=social&color=white)](https://github.com/plone/plone/stargazers) — Mature Python enterprise CMS with headless capabilities and very strong security/accessibility track record.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects that support content modeling and modern APIs (REST/GraphQL).

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — the open-source headless CMS ecosystem is thriving! 🚀

