## Magento 2 Improved Polish Language Pack

## Installation via Composer:
### latest version:
`composer require jq-dev/magento2-improved-polish-language-pack`

### or specific version:
`composer require jq-dev/magento2-improved-polish-language-pack:1.1.4`

## Setup:
- php bin/magento setup:static-content:deploy pl_PL
- in dashboard go to 'Account Setting' and change the 'Interface Locale' to "Polski (Polska)"
- in dashboard go to 'Stores' > 'Configuration' > 'General' > 'Locale options: Locale' and set 'polski (Polska)'
- php bin/magento cache:flush
