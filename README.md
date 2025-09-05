## Friendly Guacamole

This project sets up a minimal Django application with a Vue.js front end.

### Setup

Dependencies are managed with [uv](https://github.com/astral-sh/uv). Attempt to install Django with:

```bash
uv add django
```

### Running

```bash
uv run python manage.py runserver
```

### Front End

Vue is loaded via CDN in the `home` template.

