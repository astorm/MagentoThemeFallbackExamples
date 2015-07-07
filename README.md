MagentoThemeFallbackExamples
============================

Some code samples for an article on Magento 1.9's new theme fallback mechanism. 

Contains a single Magento design package `pulsestorm`.

This design package contains two themes, `default` and `a`.

The `pulsestorm/default` theme is a child of `rwd/default` (the new responsive web design theme)

The `pulsestorm/a` theme is a child of `pulsestorm/default`.

The intent of these samples, along with their [parent article](http://alanstorm.com/magento_infinite_fallback_theme_xml), is to demonstrate how standard Magento layout XML files fall under infinite inheritance, while `theme.xml` specific files fall outside of multiple inheritance. 
