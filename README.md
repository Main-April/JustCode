# Just ... Code !

Just Code is a JavaScript library created to accelerate the development of all kinds of websites.

## Installation

Include these script tags in your HTML file:

### Import Installer File
```html
<script src="https://raw.githack.com/Main-April/Nanotypes.js/main/installer.js"></script>
```
Installer File automatically import all file in the Main folder.
You can use the plugin with the function importFile(String filename) 

### Complete Setup Example
```html
<!DOCTYPE html>
<html>
<head>
    <title>Unnamed Project</title>
</head>
<body>
    <!-- Your content -->
   <script src="https://raw.githubusercontent.com/Main-April/Nanotypes.js/refs/heads/main/installer.js"></script>
</body>
</html>
```

## Usage

### DOM Utilisation

You can use the select function to select elements using `select(String s)` function, like $ Jquery syntax :

```javascript
// If you have an element like this :
// <button>send</button>
select("button").onclick = alert("Button clicked !")

```

## Features

- **Lightweight**: Minimal file size for fast loading
- **No Dependencies**: Works directly in any modern browser
- **Plugin System**: Extend functionality with additional modules
