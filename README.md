# loading.css

>  In progress :hourglass_flowing_sand:


## Usage

1. Include the stylesheet on your document's `<head>`

```html
<head>
<link rel="stylesheet" type="text/css" href="/path/to/loading.min.css">
</head>
```

2. Add the `loading` class followed by the appropriate [class name](#loading-style-classes) of  for the spinner.

Example:
```html
<div class="loading ldgRing"></div>
````
## Loading style classes

- `ldgBalls`
- `ldgBar`
- `ldgBattery`
- `ldgDualRing`
- `ldgFlip`
- `ldgRing`
- `ldgSignal`
- `ldgSquare`


## File Structure

```
loading.css/
|-- docs                            // Examples
|   |-- index.html
|   |-- loading.css
|   |-- loading.min.css
|
|-- src/                            // Source Stylus files
|   |-- _efects/
|   |    |-- _balls.styl
|   |    |-- _bar.styl
|   |    |-- ...
|   |-- base.styl
|   |-- loading.styl
|
|-- loading.css
|-- loading.min.css
|-- package.json
|-- ...
````

# License

Licensed under the [MIT License](LICENSE)
