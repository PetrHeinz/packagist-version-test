# packagist-version-test

Repo made for testing versions in format SERIES.MAJOR.MINOR.PATCH, eg. 7.1.0.0

Tested using a package `petr-heinz/packagist-version-test` registered on Packagist and [semver.mwl.be](https://semver.mwl.be/#?package=petr-heinz%2Fpackagist-version-test).

---

**Results:**

Packagist parses it as MAJOR.MINOR.PATCH.BUILD, meaning Composer would not expect a BC break between 7.1.3.10 and 7.2.0.0

See the difference between [^7.0.0.0](https://semver.mwl.be/#?package=petr-heinz%2Fpackagist-version-test2&version=%5E7.0.0.0&minimum-stability=stable) and [>=7.0.0.0 <7.1](https://semver.mwl.be/#?package=petr-heinz%2Fpackagist-version-test2&version=%3E%3D7.0.0.0%20%3C7.1&minimum-stability=stable).
