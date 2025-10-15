# ntfy-action

Gitea Actions ntfy notification action

### Usage:

```yaml
- name: Notify
  uses: jmitech/ntfy-action@v1
  with:
    title: "My Job"
    message: "Image build completed for branch X\nSHA: abc123"
    tags: whale
```
