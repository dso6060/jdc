<p align="center">JUSTICE DEFINTIONS PROJECT</p>

---

<br>

<p>
This project aims to make legal language accessible by connecting any webpage selection to a reliable community‑maintained <a href="https://jdc-definitions.wikibase.wiki/wiki/The_Justice_Definitions_Project">Justice Definitions Project</a>. Built for researchers, students, and practitioners, the extension lets you select a term on any page and instantly shows a concise
definition preview sourced from the Justice Definitions Project (MediaWiki), curated and reviewed
by experts. The goal is to provide credible, up‑to‑date explanations
grounded in Indian legal context while remaining easy to consult during everyday reading.
</p>
  
<br>


### Installation 🧩

**Chrome Extension (Development Version):**
1. Download or clone this repository
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode" (toggle in top right)
4. Click "Load unpacked" and select this project folder
5. The extension will appear in your Chrome toolbar

### What this extension does

- Select any word/term on a webpage and open the extension popup
- The extension searches the Justice Definitions Project for the most relevant page
- It displays the first 140 characters from the page intro and links to the source, so you can read more in context

### Known Issues & Troubleshooting

**⚠️ Webhook Configuration (Optional):**
- The "Request Definition" feature requires a Google Apps Script webhook URL
- If you see "Configure request endpoint first" error, this is normal - the webhook is optional
- To enable request submissions: Right-click extension → Options → Enter your Apps Script URL
- Without webhook: Extension works perfectly for looking up existing definitions
- With webhook: Can submit requests for missing definitions to a Google Sheet

**Icon Not Updating:**
- If the extension still shows the old "Aa" icon instead of "J":
  1. Go to `chrome://extensions/`
  2. Click the refresh icon on the extension
  3. Or remove and reload the extension

### Why “reliable” Justice Definitions

We are evolving this effort toward an expert‑curated, credible knowledge base for legal terminology.
The intent is to reduce ambiguity and ensure reliability by incorporating:

- Expert review workflows (domain experts vet definitions and updates)
- Transparent sourcing and citations
- Versioned changes and public discussion for key updates

While the extension already integrates with the Justice Definitions Project, the “credible”
designation reflects the ongoing work to formalise governance, review, and publishing standards.

### Governance and contributions

- Editorial guidance: legal academics and practitioners help set standards
- Review flow: submissions and edits are reviewed by experts before publication
- Community: students, researchers, and contributors can propose improvements and citations

If you’re an expert or institution and would like to participate in curation,
please open an issue or reach out to collaborate.

### Open Source

This repository is open source. Developers can use it as a reference to build their own extensions
or contribute enhancements here. Please attribute the original author and the Justice Definitions
Project when reusing significant parts of the code or documentation.

<br>

### Attribution

Part of this code-base was originally created and open‑sourced by **[Sandeep Suman](https://github.com/SandeepKrSuman)**.
The current version adapts the lookup to use the **Justice Definitions Project** (MediaWiki) as the primary
data source for legal terms, fetching a page intro and displaying the first 140 characters with a link back
to the source. Prior versions referenced the Free Dictionary API for general‑purpose terms.

- Original author: [SandeepKrSuman](https://github.com/SandeepKrSuman)
- Previous data source: [freeDictionaryAPI](https://github.com/meetDeveloper/freeDictionaryAPI)
- Current data source: <a href="https://jdc-definitions.wikibase.wiki/wiki/The_Justice_Definitions_Project">Justice Definitions Project</a>

<br>

### Built on Justice Definitions content

This browser extension is a plugin built on top of the content created and maintained by the open‑source team behind the **Justice Definitions Project**. We gratefully acknowledge their work in curating reliable legal definitions and citations.

### Repository Status

**🔓 Public Repository:** This project is open source and publicly available on GitHub.

**📋 Current Status:**
- ✅ Core functionality working (JDP lookups)
- ✅ Clean J-themed icons
- ✅ Optional webhook configuration
- ⚠️ Webhook setup requires manual Google Apps Script configuration
- 🔄 Version 0.5.1 (latest)

**🐛 Known Issues:**
1. **Webhook Error Messages:** Users may see "Configure request endpoint first" - this is expected behavior when no webhook is configured
2. **Icon Caching:** Chrome may cache old icons - refresh extension to see new J icon
3. **Development Only:** This is a development version, not published to Chrome Web Store

<br>

### License

[MIT](LICENSE) © [SandeepKrSuman](https://github.com/SandeepKrSuman)


 
