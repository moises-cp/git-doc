# Pull

## Unrelated History

Error when pulling

```
fatal: refusing to merge unrelated histories
```

Solution

- Add the flag `--allow-unrelated-histories`

Example

```
git pull origin main --allow-unrelated-histories
```
