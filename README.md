# Media WYSIWYG

This module provides a Drupal 7 to 8 migration from Publisher's media_wysiwyg
module to entity_embed module.

It loops field instances and defines a plugin (MediaWysiwyg) per entity type
to perform the alterations on the respective migrations. If an entity
type does not have a corresponding plugin, a warning will be logged.
