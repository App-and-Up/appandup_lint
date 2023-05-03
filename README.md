# appandup_lint

App and Up SRL Lint preferences for Dart and Flutter applications

## How to use this package

The appandup_lint package doesn't ship any dart source code.

To enable `appandup_lint`,
1. Add it to your dev_dependencies
```yaml
dev_dependencies:
  appandup_lint: ^0.0.5
```

2. Include the rules into your `analysis_options.yaml`
```yaml
include: package:appandup_lint/recommended.yaml
```

3. If the project is using Riverpod, add the following line to your `analysis_options.yaml` as well.
```yaml
include: package:appandup_lint/riverpod.yaml
```

4. Run `flutter analyze` to see the errors and warnings
