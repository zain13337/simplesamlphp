# Upgrade notes for SimpleSAMLphp 2.2

SimpleSAMLphp 2.2 is a minor new release which introduces a few new features.
The following changes are relevant for installers and/or developers.

## Deprecations

The following methods were marked `deprecated` and will be removed in a next major release.

- SimpleSAML\Error\ErrorCodes::defaultGetAllErrorCodeTitles - Use getDefaultTitles instead
- SimpleSAML\Error\Errorcodes::getCustomErrorCodeTitles - Use getCustomTitles instead
- SimpleSAML\Error\Errorcodes::getAllErrorCodeTitles - Use getAllTitles instead
- SimpleSAML\Error\Errorcodes::defaultGetAllErrorCodeDescriptions - Use getDefaultDescriptions instead
- SimpleSAML\Error\Errorcodes::getCustomErrorCodeDescriptions - Use getCustomErrorCodeDescriptions instead
- SimpleSAML\Error\Errorcodes::getAllErrorCodeDescriptions - Use getAllDescriptions instead
- SimpleSAML\Error\Errorcodes::getAllErrorCodeMessages - Use getAllMessages instead
- SimpleSAML\Error\Errorcodes::getErrorCodeTitle - Use getTitle instead
- SimpleSAML\Error\Errorcodes::getErrorCodeDescription - Use getDescription instead
- SimpleSAML\Error\Errorcodes::getErrorCodeMessage - Use getMessage instead
