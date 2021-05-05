# Pytest


- all the testing function should start with "test_".
	- Example 
	``` 
	def test_check_output():
		# code
		pass
	```
- Pytest finds the testing function automatically.


## Fixtures
- Pytest fixtures can initilize test function
	- for example: can make a setup for executing particular test
- fixtures are in modular mannar
- can be used as a decorator - __@pytest.fixture__