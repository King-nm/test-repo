# Holloway Connect

Static public intake and admin CRM page for Holloway Connect.

## Local Preview

```powershell
python -m http.server 5182 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:5182/index.html
```

## GitHub Pages

This folder is ready to publish from the repository root with GitHub Pages.

In GitHub, use:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

## Data Collection

The current fallback CRM stores leads in browser `localStorage`. For live collection across visitors, connect the form to a shared backend such as Supabase, Netlify Forms, Airtable, or a small API service.
