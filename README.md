# vh-ad-images

Rendered-ad preview screenshots for VitaHustle Meta ads, one JPEG per ad:
`previews/<ad_id>.jpg` — the full ad unit (identity header, copy, media/poster,
CTA card) captured logged-out from the Meta Graph previews-edge iframe.

Auto-published by `ad_preview_screenshot_sync.py` (daily launchd cron
`ai.hermes.cron.vita-ad-preview-screenshots` on the VitaHustle Mac mini).
Index/metadata lives in `meta_ads_tw.ad_preview_screenshots` (openclaw_vitahustle).

Consumed via raw URLs (`raw.githubusercontent.com/holdenjrussell/vh-ad-images/main/previews/<ad_id>.jpg`)
by the VitaHustle MCP tools `vh_ad_preview_links` / `vh_ad_creative_media` for
deck building in sandboxed environments. These are screenshots of publicly
served ads.
