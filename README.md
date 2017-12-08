# Broken

* cd to test-runner and install deps
* run `yarn jest --testPathIgnorePatterns=['']`
* no tests will run

---

# To fix

* rename the top-level folder to anything other than "node_modules"
* cd to test-runner and install deps
* run `yarn jest` or `yarn jest --testPathIgnorePatterns=['']`
* test will run

