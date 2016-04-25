# Code

The code for this lecture is broken down into three sections.

### Beginning

The "beginning" folder contains a few spec.js files that follow the slides as we build up to a full "describe full of it's with beforeEach's" file.

### Seed Specs

This folder contains the bare-bones skeleton for a unit test. When you create a new component and want to make a unit test for it you can copy this template and begin coding your tests from here. As a bonus I've also provided a seed file for Protractor e2e tests.

### Test Runner Sample

This is a fully built out project (based on the yeoman generator Gulp-Angular) ready for you to dig in and start running tests. Here are the steps to get it up and running:

1. from command line, cd into the 'test-runner-example' directory.

2. Run the following command:

    npm install
    
    
3. Once it has finished, run this command:

    bower install
    

That's it! Now from the command line you should be able to run these gulp tasks:

- `$ gulp` to build an optimized version of your application in folder dist
- `$ gulp serve` to start BrowserSync server on your source files with live reload
- `$ gulp serve:dist` to start BrowserSync server on your optimized application without live reload
- `$ gulp test` to run your unit tests with Karma
- `$ gulp test:auto` to run your unit tests with Karma in watch mode
- `$ gulp protractor` to launch your e2e tests with Protractor
- `$ gulp protractor:dist` to launch your e2e tests with Protractor on the dist files
  
