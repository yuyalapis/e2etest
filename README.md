# e2etest
Simple End-to-End Test for web [![PyPI Downloads](https://static.pepy.tech/badge/e2etest/month)](https://pepy.tech/projects/e2etest)

## Usage
```
pip install e2etest
```

```python
from e2etest import E2E
url = "https://lapisai.com/query"
e2e = E2E(url)
e2e.render()
assert e2e.exists("p") == True
assert "This Title" in e2e.get_text("p")
```
