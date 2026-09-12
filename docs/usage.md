# Usage

The README covers the basics. This page collects the
longer examples and the notes that did not fit up front.

## Basic

```bash
curl -X POST localhost:5000/notes \
  -H 'content-type: application/json' \
  -d '{"title": "first", "body": "hello"}'
```

## Notes

- pytest coverage for the happy paths
- CRUD endpoints for notes
