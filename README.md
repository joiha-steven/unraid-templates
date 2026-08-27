# Unraid templates

Docker templates for [Unraid](https://unraid.net)'s Docker tab.

| App | What it is |
|---|---|
| [Quire Ink](./quireink.xml) | A self-hosted blog in one container — real editor, newsletters, comments, analytics, eleven languages, no third-party requests. [Website](https://quireink.com) · [Source](https://github.com/joiha-steven/quireink) |

## Using a template before it reaches Community Applications

Unraid → **Docker** tab → scroll to **Template Repositories** → add:

```
https://github.com/joiha-steven/unraid-templates
```

Save, then **Add Container** and pick the template from the dropdown.

## First run, for Quire Ink

The blog has no owner until you claim it. Open the container's log right after it starts —
it prints a one-time claim link. Open that link, create your account, and the rest happens
in the browser.
