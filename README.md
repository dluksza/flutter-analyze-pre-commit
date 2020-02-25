# Flutter Analyze `pre-commit`

[`pre-commit`](https://pre-commit.com) hook for running Flutter anlyzer

Add the following in your `.pre-commit-config.yaml`:
```yaml
- repo: https://github.com/dluksza/flutter-analyze-pre-commit
  rev: "master"
  hooks:
    - id: flutter-analyze
```

## Acknowledgements

[Charles Crete](https://github.com/Cretezy/) for creating `flutter-format-pre-commit`
