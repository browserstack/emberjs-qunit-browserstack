# emberjs-qunit-browserstack (Using BrowserStack Runner)

### Installation

* `yarn`

### Configuration

### Parameters for `browserstack.json`

 * `username`: BrowserStack username (Or `BROWSERSTACK_USERNAME` environment variable)
 * `key`: BrowserStack [access key](https://www.browserstack.com/accounts/local-testing) (Or `BROWSERSTACK_KEY` environment variable)
 * `test_path`: Path to the test page which will run the tests when opened in a browser.

### Running Tests locally

* `ember serve` Note: if ember is not present in the path then use `./node_modules/.bin/ember`
* visit [http://localhost:4200/tests](http://localhost:4200/tests).

### Running Tests on Browserstack

* `ember serve` Note: if ember is not present in the path then use `./node_modules/.bin/ember`
* `./node_modules/.bin/browserstack-runner`
