# e2etest
Simple End-to-End Test for web

## Usage
```
pip install e2etest
```

```python
from e2etest import E2E
e2e = E2E(url)
assert e2e.exists("p") == True
assert "This Title" in e2e.get_text("p")
```
