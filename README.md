[![](https://img.shields.io/pypi/pyversions/self.svg?maxAge=86400)](https://pypi.org/pypi/self/)
[![](https://img.shields.io/pypi/v/self.svg?maxAge=86400)](https://pypi.org/pypi/self/)
[![](https://img.shields.io/badge/libraries.io-self-green.svg?maxAge=86400)](https://libraries.io/pypi/self)

[![CodeFactor](https://www.codefactor.io/repository/github/looking-for-a-job/self.py/badge)](https://www.codefactor.io/repository/github/looking-for-a-job/self.py)
[![CodeClimate](https://codeclimate.com/github/looking-for-a-job/self.py/badges/gpa.svg)](https://codeclimate.com/github/looking-for-a-job/self.py)
[![Scrutinizer](https://scrutinizer-ci.com/g/looking-for-a-job/self.py/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/looking-for-a-job/self.py/)
[![BetterCodeHub](https://bettercodehub.com/edge/badge/looking-for-a-job/self.py?branch=master)](https://bettercodehub.com/results/looking-for-a-job/self.py)
[![Sonarcloud](https://sonarcloud.io/api/project_badges/measure?project=self.py&metric=code_smells)](https://sonarcloud.io/dashboard?id=self.py)

[![Codecov](https://codecov.io/gh/looking-for-a-job/self.py/branch/master/graph/badge.svg)](https://codecov.io/gh/looking-for-a-job/self.py)
[![CircleCI](https://circleci.com/gh/looking-for-a-job/self.py/tree/master.svg?style=svg)](https://circleci.com/gh/looking-for-a-job/self.py/tree/master)
[![Scrutinizer](https://scrutinizer-ci.com/g/looking-for-a-job/self.py/badges/build.png?b=master)](https://scrutinizer-ci.com/g/looking-for-a-job/self.py/)
[![Semaphore CI](https://semaphoreci.com/api/v1/looking-for-a-job/self-py/branches/master/shields_badge.svg)](https://semaphoreci.com/looking-for-a-job/self-py)
[![Travis](https://api.travis-ci.org/looking-for-a-job/self.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/self.py/)

### Install

```bash
$ [sudo] pip install self
```

### Usage

```python
>>> from self import self

>>> @self
	def method(self):
```

### Examples

```python
>>> class CLS:
	@self
	def method(self):
		print("test")

	@self
	def method2(self):
		print("test")

>>> CLS().method().method2() # jQuery like chain
```

### Sources

+   [`self.self(method, self, *args, **kwargs)`](https://github.com/looking-for-a-job/self.py/blob/master/self/__init__.py)