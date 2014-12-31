# cucumber-junit

Converts CucumberJS JSON output into JUnitXML for software like Jenkins to read.

## Install

cucumber-junit should be added to your test codebase as a dev dependency.  You can do this with:

``` shell
$ npm install protractor-cucumber-junit --save-dev 
```

Alternatively you can manually add it to your package.json file:

``` json
{
  "devDependencies" : {
    "protractor-cucumber-junit": "latest"
  }
}
```

then install with:

``` shell
$ npm install --dev
```

## Run

protractor-cucumber-junit will convert your protractor cucumber test result to JUnitXML

``` shell
$ cat tests/features/cucumber_report.json | ./node_modules/.bin/cucumber-junit > tests/features/cucumber_report.xml
```

## License

[MIT](http://opensource.org/licenses/MIT)
