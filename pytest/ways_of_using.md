# The different ways we can use pytest

## 1. Normal asserting

```
	def func(x):
	    return x + 1

	def test_answer():
	    assert func(3) == 5
```

#### Command
> pytest


## 2. Asserting Exceptions

```
import pytest


def f():
    raise SystemExit(1)


def test_mytest():
    with pytest.raises(SystemExit):
        f()
```

## 3. Grouping multiple tests into class

- Classname should start with __Test__

```
class TestClass:
    def test_one(self):
        x = "this"
        assert "h" in x

    def test_two(self):
        x = "hello"
        assert hasattr(x, "check")
```


## -1. Create own explanation for failure of asserting
[ref](https://docs.pytest.org/en/6.2.x/assert.html#defining-your-own-explanation-for-failed-assertions)


All [ref](https://docs.pytest.org/en/6.2.x/getting-started.html#group-multiple-tests-in-a-class)



