Karma + Mocha + Chai + Sinon
----------------------------
> [Karma](http://karma-runner.github.io/0.12/index.html) is essentially a tool which spawns a web server that executes source code against test code for each of the browsers connected. The results for each test against each browser are examined and displayed via the command line to the developer such that they can see which browsers and tests passed or failed.
>
> [Mocha](http://visionmedia.github.io/mocha/) is a feature-rich JavaScript test framework running on node.js and the browser, making asynchronous testing simple and fun. Mocha tests run serially, allowing for flexible and accurate reporting, while mapping uncaught exceptions to the correct test cases. Hosted on GitHub.
>
> [Chai](http://chaijs.com/) is a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.
>
> [Sinon](http://sinonjs.org/) for standalone test spies, stubs and mocks for JavaScript.
No dependencies, works with any unit testing framework.

* [package.json](https://github.com/goodeggs/garbanzo/blob/master/package.json#L146-L153)
* [karma](https://github.com/goodeggs/garbanzo/blob/1130fa0a161b0d145e544cce21514a059b773618/Gruntfile.coffee#L507-L525)  
* [mobileClientSpecs](https://github.com/goodeggs/garbanzo/blob/1130fa0a161b0d145e544cce21514a059b773618/Gruntfile.coffee#L200-L204)
* [spec:mobile](https://github.com/goodeggs/garbanzo/blob/master/app/lib/tasks/grunt/specs.coffee#L62)
* [thankyou_page.spec](https://github.com/goodeggs/garbanzo/blob/master/src/mobile/spec/client/checkout/pages/thankyou_page.spec.coffee)  


Next Steps
----------

* Sourcemaps in stacktraces: [exorcise](https://github.com/mikefrey/grunt-exorcise) + [karma-sourcemap-loader](https://github.com/demerzel3/karma-sourcemap-loader)
* Run specs from Rubymine
* Run single specs
* Jasmine -> Mocha/Chai/Sinon everywhere?
