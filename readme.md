# mirrors autoflake

autoflake support pre-commit now: https://github.com/myint/autoflake/pull/62

mirror <https://github.com/myint/autoflake>

```yaml
- repo: https://github.com/Trim21/mirrors-autoflake
  rev: ''
  hooks:
    - id: autoflake
      args: ['--in-place']
```
