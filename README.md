Karma
-----
> [Karma](http://karma-runner.github.io/0.12/index.html) is essentially a tool which spawns a web server that executes source code against test code for each of the browsers connected. The results for each test against each browser are examined and displayed via the command line to the developer such that they can see which browsers and tests passed or failed.

**Gruntfile.coffee**
* [karma](https://github.com/goodeggs/garbanzo/blob/1130fa0a161b0d145e544cce21514a059b773618/Gruntfile.coffee#L507-L525)  
* [mobileClientSpecs](https://github.com/goodeggs/garbanzo/blob/1130fa0a161b0d145e544cce21514a059b773618/Gruntfile.coffee#L200-L204)

**Specs**  
* [spec:mobile](https://github.com/goodeggs/garbanzo/blob/master/app/lib/tasks/grunt/specs.coffee#L62)
* [thankyou_page.spec](https://github.com/goodeggs/garbanzo/blob/master/src/mobile/spec/client/checkout/pages/thankyou_page.spec.coffee)  


Next Steps
----------

**Sourcemaps in stacktraces**  
* [exorcise](https://github.com/mikefrey/grunt-exorcise) + [karma-sourcemap-loader](https://github.com/demerzel3/karma-sourcemap-loader)
