# syliusbrandplugin
This a brand plugin that add brands to sylius project and this   . 

#  Installation 

# Step1: Dowload the plugin 


Open a command console, enter your project directory and execute the following command to download the latest stable version of this bundle:

$ composer require loevgaard/sylius-brand-plugin

This command requires you to have Composer installed globally, as explained in the installation chapter of the Composer documentation.

# Step2: Enable the plugin

Then, enable the plugin by adding it to the list of registered plugins/bundles in config/bundles.php file of your project before (!) SyliusGridBundle:

```php
<?php

# config/bundles.php

return [
    // ...
    Loevgaard\SyliusBrandPlugin\LoevgaardSyliusBrandPlugin::class => ['all' => true],
    Sylius\Bundle\GridBundle\SyliusGridBundle::class => ['all' => true],
    // ...
];

```



