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

On static hosting, submissions are sent through FormSubmit to:

```text
Kingholloway01@gmail.com
```

The first live submission may send an activation email from FormSubmit. Confirm it once, then new leads should arrive by email.

The browser CRM still keeps a local `localStorage` copy for the current browser. For a shared admin dashboard across devices, add a database backend such as Supabase.
