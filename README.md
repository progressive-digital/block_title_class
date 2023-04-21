# block_title_class
Provides a possibility to add a headline class (h1 - h6) to the block title.

## How to include it in your Drupal project
Add the repository to your composer.json like this:
```json
"repositories": [
  {
      "type": "composer",
      "url": "https://packages.drupal.org/8"
  },
  {
    "type": "git",
    "url": "https://github.com/progressive-digital/block_title_class.git"
  }
]
```

And then require this module:
```bash
composer require 'progressive-digital/block_title_class:^1.0'
```

## HTML in Block
```twig
<h2{{ title_attributes }}>{{ label }}</h2>
```
