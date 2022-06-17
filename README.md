## Magento 2 Improved Polish Language Pack

## Installation via composer
- composer require JQ-dev/magento2-improved-polish-language-pack:1.0.1
- php bin/magento setup:static-content:deploy pl_PL
- in dashboard go to 'Account Setting' and change the 'Interface Locale' to "Polski (Polska)"
- in dashboard go to 'Stores' > 'Configuration' > 'General' > 'Locale options: Locale' and set 'polski (Polska)'
- php bin/magento cache:flush

:information_source: Developed and tested on Magento 2.4.3
