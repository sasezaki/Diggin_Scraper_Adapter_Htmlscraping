Diggin_Scraper_Adapter_Htmlscraping
===================================

Master: [![Build Status](https://travis-ci.org/diggin/Diggin_Scraper_Adapter_Htmlscraping.png?branch=master)](https://travis-ci.org/diggin/Diggin_Scraper_Adapter_Htmlscraping)

- This package aims to used by Diggin_Scraper.
- But, this component is useful as standalone.

### USAGE

``` php
<?php
use Diggin\Scraper\Adapter\Htmlscraping\Htmlscraping;

$htmlscraping = new Htmlscraping;
$htmlscraping->getXhtml((new Zend\Http\Client)->setUri($url)->send());

```
