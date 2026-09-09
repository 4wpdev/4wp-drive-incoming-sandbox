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

- [`4wp-drive-plugin-overview/`](4wp-drive-plugin-overview/) — test material: an overview of the 4WP Drive plugin's capabilities.

Sources: the [plugin page on WordPress.org](https://wordpress.org/plugins/4wp-drive/), the [4wpdev/4wp-drive repository](https://github.com/4wpdev/4wp-drive).
