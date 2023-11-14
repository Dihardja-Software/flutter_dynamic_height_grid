# Dynamic Height Grid
<p>
	<a href="https://pub.dev/packages/dynamic_height_grid" rel="noopener" target="_blank"><img src="https://img.shields.io/pub/v/dynamic_height_grid.svg" alt="Pub.dev Badge"></a>
	<a href="https://github.com/Dihardja-Software/flutter_dynamic_height_grid" rel="noopener" target="_blank"><img src="https://img.shields.io/badge/platform-flutter-ff69b4.svg" alt="Flutter Platform Badge"></a>
</p>

Lazy load grid view with dynamic height for each row

## Usage
```dart
DynamicGridView(
    padding: const EdgeInsets.all(16),
    builder: (BuildContext context, int index) {
        // item builder
    },
    itemCount: list.length,
    crossAxisCount: 3,
),
```

<img src="https://raw.githubusercontent.com/Dihardja-Software/flutter_dynamic_height_grid/master/doc/assets/dynamic_grid.PNG" />

## License

[MIT](https://choosealicense.com/licenses/mit/)
