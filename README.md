# omega_flutter_lint
Flutter lint rules

# How to use
To use the lints add a dev dependency in your `pubspec.yaml`:
```yaml
dev_dependencies:
  omega_flutter_lint:
    git:
      url: https://github.com/Omega-R/omega_flutter_lint.git
      ref: v0.0.2
```

Then add an include in your `analysis_options.yaml` file:
```yaml
include: package:omega_flutter_lint/analysis_options.yaml
```