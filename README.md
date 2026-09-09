# 4wp-drive-incoming-sandbox

Sandbox repository for incoming materials that the **4WP Drive** plugin imports into WordPress (a GitHub-based equivalent of the `incoming/` folder on Google Drive).

## Structure

Each folder is one importable package:

```
<folder-slug>/
  article.md   — article with front-matter (Title, Slug, Category, Tags, Date, Author) + a --- or ===== separator
  cover.png    — a file with "cover"/"featured"/"hero"/"thumbnail" in its name is auto-assigned as the featured image
```

## Examples

- [`4wp-drive-plugin-overview/`](4wp-drive-plugin-overview/) — overview of the 4WP Drive plugin's capabilities.
- [`4wp-advanced-code-overview/`](4wp-advanced-code-overview/) — overview of the 4WP Advanced Code plugin's capabilities.
- [`4wp-notifications-overview/`](4wp-notifications-overview/) — overview of the 4WP Notifications plugin's capabilities.

All materials in this repository are English-only.
