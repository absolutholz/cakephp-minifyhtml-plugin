## CakePHP 2.x HTML Minify Plugin

This is a plugin for CakePHP to minify the HTML output.

### Requirements:

* PHP Version: 5.2+
* CakePHP Version: 2.x

### Installation:

_[GIT Submodule]_

In your app directory (`app/Plugin`) type:

```bash
git submodule add git://github.com/absolutholz/cakephp-minifyhtml-plugin.git app/Plugin/MinifyHtml
git submodule init
git submodule update
```

_[GIT Clone]_

In your plugin directory (`app/Plugin` or `plugins`) type:

```bash
git clone https://github.com/absolutholz/cakephp-minifyhtml-plugin.git Markdown
```

## Usage

```php
// in app/Controller/AppController.php
public $helpers = array('MinifyHtml.MinifyHtml');
```
