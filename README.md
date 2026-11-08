# Awesome-Visual-App-Design-Low-Code-Studio

# Awesome Visual App Design & Low-Code Studio

> A curated list of top Visual App Design and Low-Code Studio platforms — both SaaS/Hosted commercial solutions and open-source alternatives for building internal tools, admin panels, and business applications with drag-and-drop interfaces.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [OutSystems](#outsystems)
  - [Mendix](#mendix)
  - [Microsoft Power Apps Studio](#microsoft-power-apps-studio)
  - [Retool](#retool)
  - [Appian Studio](#appian-studio)
  - [FlutterFlow](#flutterflow)
  - [Bubble](#bubble)
  - [Glide](#glide)
  - [Webflow](#webflow)
- [Open-Source Software](#-open-source-software)
  - [Appsmith](#appsmith)
  - [ToolJet](#tooljet)
  - [Budibase](#budibase)
  - [Lowcoder](#lowcoder)
  - [Windmill](#windmill)
  - [Joget DX](#joget-dx)
  - [Convertigo](#convertigo)
  - [Baserow](#baserow)
  - [NocoDB](#nocodb)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Visual App Design and Low-Code Studio platforms. These are not open-source but are included as reference points for feature comparison.

### OutSystems
**Type:** Enterprise low-code platform  
OutSystems is a long-standing enterprise low-code platform for building web and mobile applications with visual modeling, full-stack capabilities, and deployment automation. Known for enterprise governance, lifecycle management, and integration depth. Pricing is quote-based and typically targets mid-to-large enterprises.

### Mendix
**Type:** Enterprise low-code with model-driven development  
Mendix (Siemens) provides a visual development environment with model-driven architecture, multi-cloud deployment, and strong governance features. Supports collaborative development between business users and IT. Pricing is quote-based with a free tier for small teams.

### Microsoft Power Apps Studio
**Type:** Low-code app builder within Power Platform  
Power Apps Studio provides a drag-and-drop canvas for building business apps connected to Microsoft 365, Dynamics 365, and hundreds of connectors. Includes Power Fx formula language and integration with Power Automate flows. Best suited for organizations already in the Microsoft ecosystem.

### Retool
**Type:** Internal tool builder for developers  
Retool is a widely adopted platform for building internal tools, admin panels, and dashboards with drag-and-drop components and connections to databases and APIs. Includes a JavaScript code editor for custom logic. Pricing is per-user with a free tier for small teams.

### Appian Studio
**Type:** Low-code automation with process orchestration  
Appian's low-code platform combines visual app design with process automation, case management, and AI capabilities. Strong in regulated industries needing audit trails and compliance controls. Pricing is quote-based.

### FlutterFlow
**Type:** Visual Flutter app builder  
FlutterFlow allows visual development of native mobile and web apps using drag-and-drop, with exportable Flutter code. Integrates with Firebase for backend services. Subscription-based pricing with a free tier for basic use [citation:4][citation:9].

### Bubble
**Type:** No-code full-stack app builder  
Bubble lets non-technical users build full-stack web applications visually, including database, workflows, and responsive design. Popular for MVPs and startups. Pricing is subscription-based with workload-based tiers.

### Glide
**Type:** No-code app builder from data sources  
Glide builds apps from Google Sheets, Airtable, and other data sources with a visual editor. Focused on simplicity for business users creating internal apps and directories. Pricing is per-user with a free tier.

### Webflow
**Type:** Visual web design and CMS  
Webflow provides visual design control for building responsive websites with CMS capabilities. While not a full app builder, it includes logic and e-commerce features. Pricing is tiered by site plans and CMS items.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Visual App Design and Low-Code Studio platforms. All listed projects offer source code you can deploy on your own infrastructure.

### Appsmith
**Stack:** Java / React / MongoDB | **License:** Apache-2.0 (Open-Core)  
Appsmith is a low-code platform for building admin panels, CRUD apps, and internal tools with a drag-and-drop interface and 45+ pre-built widgets . Connects to 20+ databases (PostgreSQL, MySQL, MongoDB) and any REST or GraphQL API. Features include JavaScript code editor, Git-based version control, role-based access, SSO/LDAP, and one-click Docker or Kubernetes deployment . With a large community and active development, it is one of the most mature open-source Retool alternatives.  
**Best for:** Developers wanting a proven, self-hosted platform for internal tools with strong database integrations and Git workflow support.

### ToolJet
**Stack:** Node.js / React | **License:** GPL-3.0  
ToolJet is an open-source low-code framework positioned as an alternative to Retool and Mendix . Provides a visual app builder with drag-and-drop components, connections to databases and APIs, and JavaScript for custom logic. Includes multi-page apps, team collaboration, and self-hosted deployment via Docker.  
**Best for:** Teams wanting a permissively licensed (GPL) open-source alternative for internal tool development.

### Budibase
**Stack:** Node.js / Svelte | **License:** GPL-3.0 (Open-Core)  
Budibase is an open-source low-code platform for building internal tools, admin panels, and forms. Features include a visual builder, built-in database (or connect to external sources), automation workflows, and role-based access. Deploys via Docker, Kubernetes, or DigitalOcean. Positioned as an accessible entry point for teams new to low-code.  
**Best for:** Teams wanting a straightforward, self-hosted low-code platform with built-in database and automation.

### Lowcoder
**Stack:** Java / Node.js / React / MongoDB / Redis | **License:** AGPL-3.0 (Community Edition)  
Lowcoder is an open-source Retool alternative for building internal tools, admin panels, dashboards, and customer-facing apps with a drag-and-drop editor . Connects to databases and APIs, scriptable with JavaScript, and supports embedding. The Community Edition is self-hostable with MongoDB and Redis dependencies .  
**Best for:** Teams wanting a self-hosted Retool alternative with a familiar visual editor and JavaScript scripting.

### Windmill
**Stack:** Rust / Svelte / PostgreSQL | **License:** AGPL-3.0 (Community Edition)  
Windmill is a code-first developer platform that turns scripts (Python, TypeScript, Go, Bash, SQL) into workflows, webhooks, and UIs. Every script auto-generates a UI form from its parameters, enabling rapid internal tool creation without frontend development . Includes a visual flow builder for multi-step workflows with branching and approval steps. Claims 13x faster than Airflow for job execution. 16k+ GitHub stars .  
**Best for:** Developer teams wanting a code-first approach where scripts become UIs and workflows automatically, with strong performance characteristics.

### Joget DX
**Stack:** Java | **License:** Open Source (Community Edition)  
Joget is an open-source no-code/low-code application platform combining business process automation, workflow management, and rapid application development . Features a web-based visual builder, App Generator for quick app creation, mobile-optimized outputs, and a plugin architecture. Used by 1,800+ installations and 10,000+ community users across finance, manufacturing, and government .  
**Best for:** Organizations needing low-code with strong business process management (BPM) and workflow capabilities.

### Convertigo
**Stack:** Java | **License:** Open Source (Community Edition)  
Convertigo is an open-source, AI-boosted low-code and no-code enterprise platform with dual studios: a No Code Studio for business users and a Low Code Studio for professional developers . Offers full-stack capabilities, enterprise connectors (including legacy systems like IBM 3270/5250, AS400), offline sync, and cloud or on-premises deployment. Positioned as a sovereign alternative to Power Apps, OutSystems, and Mendix .  
**Best for:** Enterprises needing low-code with strong legacy system integration and data sovereignty (European alternative).

### Baserow
**Stack:** Python / Django / Vue.js | **License:** MIT (Open-Core)  
Baserow is an open-source no-code database and Airtable alternative. While not a full app builder, it provides a visual database interface with forms, views, and API access that can serve as a backend for low-code tools. Self-hosted via Docker.  
**Best for:** Teams wanting an open-source Airtable alternative as a data layer for their low-code applications.

### NocoDB
**Stack:** Node.js / TypeScript | **License:** AGPL-3.0  
NocoDB turns any SQL database into a smart spreadsheet interface, similar to Airtable. Provides a visual interface for database management, forms, and API generation. While not an app builder per se, it is commonly used alongside low-code tools as a data backend.  
**Best for:** Teams wanting a visual interface over existing SQL databases, often paired with Appsmith or ToolJet for app building.

---

## 📊 Comparison at a Glance

| Software | License | Type | Self-Hosted | Best For |
|----------|---------|------|-------------|----------|
| **OutSystems** | Proprietary | Enterprise low-code | ❌ | Large enterprise governance |
| **Mendix** | Proprietary | Enterprise low-code | ❌ | Model-driven enterprise apps |
| **Power Apps** | Proprietary | Microsoft low-code | ❌ | Microsoft 365 ecosystem |
| **Retool** | Proprietary | Internal tool builder | ❌ | Developer-focused internal tools |
| **Appian** | Proprietary | Low-code + BPM | ❌ | Regulated industries |
| **FlutterFlow** | Proprietary | Flutter app builder | ❌ | Mobile app MVP development |
| **Bubble** | Proprietary | No-code full-stack | ❌ | Non-technical founders |
| **Webflow** | Proprietary | Visual web design | ❌ | Marketing sites + CMS |
| **Appsmith** | Apache-2.0 | Internal tool builder | ✅ | Mature OSS Retool alternative |
| **ToolJet** | GPL-3.0 | Low-code framework | ✅ | Permissive OSS internal tools |
| **Budibase** | GPL-3.0 | Low-code platform | ✅ | Accessible entry-level OSS |
| **Lowcoder** | AGPL-3.0 | Retool alternative | ✅ | Familiar visual editor |
| **Windmill** | AGPL-3.0 | Code-first platform | ✅ | Scripts-to-UI automation |
| **Joget DX** | Open Source | Low-code + BPM | ✅ | Workflow-heavy applications |
| **Convertigo** | Open Source | Enterprise low-code | ✅ | Legacy integration + sovereignty |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Visual App Design or Low-Code Studio platform that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source (or clearly note the license if open-core).

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
