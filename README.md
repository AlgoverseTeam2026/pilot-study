## Recreating the environment


1. Clone the repo: `git clone <repo-link>`
2. CD into the repo: `cd pilot-study`
3. Use UV Sync: `uv sync`

If UV is not installed you can install it with
```bash
  curl -LsSf https://astral.sh/uv/install.sh | sh
```

## Updating the Dependencies

1. Install any necessary dependancies with `uv add <package-name>`
2. *Before* commiting, add it to the `uv.lock` file with `uv sync`
3. Commit the changes

