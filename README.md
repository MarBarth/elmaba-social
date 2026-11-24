# ELMABA Games: bio link and social videos

- `index.html`: the bio link page (GitHub Pages). Each platform links with its own source: `?s=tt` (TikTok), `?s=ig` (Instagram), `?s=yt` (YouTube).
- `v/<id>.mp4`: finished social videos. Buffer fetches them from here when it publishes, so a video must stay until its posts have gone out.

Managed by `GameKit/Tools~/social/buffer_post.py` (`stage` copies a week's videos here).
