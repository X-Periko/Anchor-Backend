Run the API from the repository root with:

```sh
uv run uvicorn src.server:app --reload
```

Set `ANCHOR_SECRET_KEY` in the environment before starting the server; it is
used to sign authentication tokens.