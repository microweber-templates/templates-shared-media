# Microweber templates — shared media

Optimized media assets for the Microweber default-content templates, served via
`raw.githubusercontent.com` so each template's `mw_default_content.zip` seed can
stay **text-only** and the main microweber repo stays lean.

## Structure

```
<TemplateName>/storage/<path>
```

The paths mirror the media references inside each template's `backup.json`
(`{SITE_URL}storage/<path>`), so serving is a direct base-URL swap.

## Raw base URL

```
https://raw.githubusercontent.com/microweber-templates/templates-shared-media/main/<TemplateName>/storage/<path>
```

## Optimization

Images are optimized to keep the repo small: JPEG quality 82 and max 1920px on
the long edge; PNG/WebP stripped of metadata and resized. Filenames are
preserved so the seed references still resolve.
