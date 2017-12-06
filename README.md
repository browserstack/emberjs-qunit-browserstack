# emberjs-qunit-browserstack (Using BrowserStack Runner)

### Installation

* `npm install`

### Configuration

### Parameters for `browserstack.json`

 * `username`: BrowserStack username (Or `BROWSERSTACK_USERNAME` environment variable)
 * `key`: BrowserStack [access key](https://www.browserstack.com/accounts/local-testing) (Or `BROWSERSTACK_KEY` environment variable)
 * `test_path`: Path to the test page which will run the tests when opened in a browser.

### Running Tests locally

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Running Tests on Browserstack

* `ember serve`
* `./node_modules/.bin/browserstack-runner`
