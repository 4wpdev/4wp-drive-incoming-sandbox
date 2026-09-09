Title: What Can the 4WP Drive Plugin Do for You?
Slug: what-can-4wp-drive-plugin-do
Category: WordPress Plugins
Tags: 4wp-drive, google-drive, github, content-import, editorial-workflow
Author: 4WP Dev

=====

# What Can the 4WP Drive Plugin Do?

**4WP Drive** is a WordPress plugin that removes manual copy-pasting between Google Docs (or GitHub) and your site. A writer drafts in a familiar editor, an editor reviews it in a built-in Inbox, and once approved, the material becomes a draft post — no copy-paste, no lost formatting.

## Key capabilities

- **Google Drive OAuth connection** with encrypted token storage
- **Folder sync** — the plugin automatically scans an `incoming/` folder for new documents and images
- **Editorial Inbox** — a document queue and workspace for reviewing content before import
- **Front-matter parsing** — title, slug, categories, tags, date, author, and SEO fields are mapped automatically, split from the body by a `---` or `=====` separator
- **GitHub Markdown support** (since version 1.4.0) — articles can be imported directly from a repository
- **Image import** — a file with `cover`, `featured`, `hero`, or `thumbnail` in its name is automatically assigned as the featured image
- **Updates to existing posts**, not just creation of new ones
- **Multilingual support via Polylang** — pick the language right at import time
- **REST API and WP-CLI** for automated syncing

## Pain points it solves

1. **Manual content transfer.** Editors used to copy text from Google Docs into Gutenberg by hand, losing formatting, links, and lists along the way — everything had to be checked and redone.
2. **A disconnected review process.** Drafts lived in Docs or GitHub, separate from the site, with no single place to see what was ready to publish and what was still under review.
3. **Metadata entered by hand.** SEO title, description, categories, slug — all typed into the admin separately, with the risk of a mistake or a missed field.
4. **Featured images picked at random.** The plugin now picks an image from the material's folder based on the filename, and you can still override it manually.
5. **Credential security.** OAuth and all Google API requests run server-side, tokens are stored encrypted — no visitor-facing tracking.

## Who it's for

Editorial teams, agencies, and content operations that already work in Google Docs or GitHub and want to publish to WordPress without manual transfer — just write, review, and click "Import."

---

*This file is test material for verifying import from the GitHub repository [4wp-drive-incoming-sandbox](https://github.com/4wpdev/4wp-drive-incoming-sandbox). Sources: the [plugin page on WordPress.org](https://wordpress.org/plugins/4wp-drive/) and the [4wpdev/4wp-drive repository](https://github.com/4wpdev/4wp-drive).*
