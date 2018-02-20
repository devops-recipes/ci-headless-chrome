# headless-chrome-shippable
Testing Headless Chrome on shippable + Karma + Mocha + Chai + Puppeteer

[![Run Status](https://api.shippable.com/projects/5a8bda04fbd2be0600a5f874/badge?branch=master)](https://app.shippable.com/github/devops-recipes/ci-headless-chrome)


- first example `npm test` runs test in chrome headless using Karma + Mocha + Chai.
- second example `npm test_search`, is based on `puppeteer` and starts chrome in headless mode and queries search results from https://developers.google.com/web/ top search box 
and prints links found in search results in console log. 
