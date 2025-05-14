# Paragon Base Paragraphs Recipe

This recipe provides a base setup for working with Paragraphs in Drupal 10/11 projects using Composer. It includes a curated set of modules and configuration to streamline building flexible, reusable content components using the Paragraphs module.

## Requirements
- Drupal 10.0 or later (Drupal 11 supported)
- Composer 2.x
- PHP 8.1 or higher

## Installation
To use this recipe in your Drupal project:

1. Add the VCS repository reference to your project's `composer.json`:
```json
"repositories": [
  {
    "type": "vcs",
    "url": "https://github.com/elevatedthird/paragon-base-paragraphs-recipe#main"
  }
]
```

2. Require the recipe via Composer:
```bash
composer require drupal_recipe/paragon_base_paragraphs_recipe
```

## What’s Included
- Core Paragraphs configuration and recommended modules
- Common field settings and display modes
- Optional packages may include:
  - paragraphs
  - paragraphs_library
  - paragraph_viewmode
  - field_group
  - entity_reference_revisions
  - dynamic_entity_reference

## Updating
When a new release is available:
```bash
composer update drupal_recipe/paragon_base_paragraphs_recipe
```

## How to run
```bash
recipe ../recipes/paragon_base_paragraphs_recipe
```

## License

[MIT](LICENSE)
