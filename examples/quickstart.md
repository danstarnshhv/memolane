# Quickstart

Fresh machine, five minutes.

```bash
pip install -r requirements.txt
flask --app app run --debug
```

Then:

```bash
curl -X POST localhost:5000/notes \
  -H 'content-type: application/json' \
  -d '{"title": "first", "body": "hello"}'
```

If nothing happens, check docs/usage.md first.
