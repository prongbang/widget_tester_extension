# widget_tester_extension

[![pub package](https://img.shields.io/pub/v/widget_tester_extension.svg)](https://pub.dartlang.org/packages/widget_tester_extension)

Widget Tester Extension for Integration Test on Flutter

## Features

- pumpUntilFound

```dart
final finderVerifyHelloText = find.text('Hello');
await tester.pumpUntilFound(finderVerifyHelloText);
```

- delay

```dart
await tester.delay(milliseconds);
```

## Getting started

```yaml
dev_dependencies:
  widget_tester_extension: ^0.0.1
```

## Usage

- Import

```dart
import 'package:widget_tester_extension/widget_tester_extension.dart';
```

- pumpUntilFound

```dart
await tester.pumpUntilFound(finder);
```

- delay

```dart
await tester.delay(500);
```
