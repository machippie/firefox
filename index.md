
## Default Variables

### firefox_started

Restart app if already running

#### Default value

```yaml
firefox_started: true
```

### firefox_user

User to run user-specific commands

#### Default value

```yaml
firefox_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
