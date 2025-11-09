# Me Not Whitespace

Use in your GitHub Workflows by including,

This Action assumes that you have fetched _all_ the branches before running this Action, because it needs to know about the **base branch**.

```yaml
- uses: ofer987/me-not-whitespace@v1
  with:
    BASE_REF: ${{ github.base_ref }}
```
