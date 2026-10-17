# TeamTreck Blog

Live site: https://teamtreck.github.io

## How to publish a new blog post (2 minutes, all in the browser)

1. Open the new-post page: https://github.com/teamtreck/teamtreck.github.io/new/main/_posts
2. File name must be: `YYYY-MM-DD-your-post-title.md`
   (example: `2026-10-20-how-we-build-teams.md`)
3. Copy everything from `post-template.md`, paste it, then change the title, date, description and text.
4. Click **Commit changes** → **Commit changes**.
5. Wait ~1 minute. The post appears on the home page, in `sitemap.xml` and in the RSS feed automatically.

## Editing or deleting a post
Open the file in the `_posts` folder, click the pencil icon to edit (or the ... menu to delete), then commit.

## Adding images
Upload images to `assets/images/` (Add file → Upload files) and use
`![description](/assets/images/file-name.png)` in your post.

## What's set up
- Theme: Minima (clean, mobile-friendly)
- `sitemap.xml` — generated automatically (jekyll-sitemap)
- `robots.txt` — allows all crawlers and points to the sitemap
- `feed.xml` — RSS feed (jekyll-feed)
- SEO meta tags on every page (jekyll-seo-tag)
- Google Search Console verified (`google35552d75c93c3569.html` — do not delete)
