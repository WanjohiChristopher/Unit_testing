# Unit_testing
[![Build Status](https://app.travis-ci.com/WanjohiChristopher/Unit_testing.svg?branch=master)](https://app.travis-ci.com/WanjohiChristopher/Unit_testing)



Filenames/modules written as : - test_

Classnames written as : - Test which is the starting point

Function names: -test_ (unit test)


### Running all tests

```
cd directory

run !pytest

To stop the test after first failure write

pytest -x
```
### Command that would only show the reason for expected failures in the test result report?

```
!pytest -rx
```
### Command that would only show the reason for skipped tests in the test result report?

```
!pytest -rs
```
#### Command that would show the reason for both skipped tests and tests that are expected to fail in the test result report?

```
!pytest -rsx
```
