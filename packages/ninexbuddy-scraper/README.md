# 9xbuddy Scraper

[![Build Status](https://travis-ci.org/OpenByteDev/SourceScraper.svg?branch=master)](https://travis-ci.org/OpenByteDev/SourceScraper)
[![npm version](https://badge.fury.io/js/ninexbuddy-scraper.svg)](https://www.npmjs.com/package/ninexbuddy-scraper)
[![Dependency Status](https://david-dm.org/OpenByteDev/SourceScraper/status.svg?path=packages%2Fninexbuddy-scraper)](https://david-dm.org/OpenByteDev/SourceScraper?path=packages%2Fninexbuddy-scraper)
[![DevDependency Status](https://david-dm.org/OpenByteDev/SourceScraper/dev-status.svg?path=packages%2Fninexbuddy-scraper)](https://david-dm.org/OpenByteDev/SourceScraper?path=packages%2Fninexbuddy-scraper&type=dev)
[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://opensource.org/licenses/MIT)
[![Doge](https://img.shields.io/badge/doge-wow-yellow.svg)]()

A scraper for [9xbuddy](https://9xbuddy.app/).

This package is part of the [SourceScraper-Project](https://github.com/OpenByteDev/SourceScraper).


## Getting Started
### Installation
```bash
$ npm i ninexbuddy-scraper
```


### Usage

```js
const { NinexbuddyScraper } = require('ninexbuddy-scraper');

(async () => {
    const url = 'some url';
    const scrap = await new NinexbuddyScraper().scrap(url);
    if (scrap.success)
        console.log(scrap.data.sources);
})();
```


### API
The API generated with [TypeDoc](http://typedoc.org/) can be found [here](https://openbytedev.github.io/SourceScraper/packages/ninexbuddy-scraper/docs/).
