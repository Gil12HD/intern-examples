grunt-example
=============

## Setup 

1. Install the JRE or JDK
   This demo runs with local Selenium, which Intern will automatically install.
   
2. Install grunt-cli
   ```
   npm install -g grunt-cli
   ```

3. Install node modules and intern

    ```
    npm install
    ```

## Running Tests

* Run `grunt test`

Check the [Gruntfile](Gruntfile.js) for details.
If you haven't used Grunt before, here are some commands that are also available using the Gruntfile in this example:
* `grunt` - runs the default task in the Gruntfile, which is `test` in this case.
* `grunt intern:client` will run intern with the default `runType: 'client'`
* `grunt intern:clientSuiteGet` will run the `get` suite.
* `grunt intern:runner` will run the `runner` subtask that has `runType: runner`, this will run the test in Chrome and
Firefox


If you need more information check out the [task documentation](https://github.com/theintern/intern/wiki/Using-Intern-with-Grunt).
