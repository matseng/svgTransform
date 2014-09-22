#jon #testing #e2e

How to count watches: http://stackoverflow.com/questions/18499909/how-to-count-total-number-of-watches-on-a-page

e2e setup and hello world example with Jon (or use grunt for protractor, etc.):

- installed protractor globally

- then get Selenium server installed and running: 
  $ cd node_module/protractor/bin/
  $ ./webdriver-manager update
  $ ./webdriver-manager start

- hosted angular page locally and configured conf.js

- set up our e2e tests, and wraped important functions within 'it' blocks to ensure $digest has time to complete
  - used CSS selectors to find elements, e.g. find a button by id

- $ protractor conf.js

