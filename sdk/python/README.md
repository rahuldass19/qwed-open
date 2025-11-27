# QWED Python SDK

Official Python client for the QWED Verification Engine.

## Installation

```bash
pip install qwed
```

## Quick Start

```python
from qwed import QwedClient

client = QwedClient(api_key="YOUR_API_KEY", base_url="http://13.71.22.94:8000")
result = client.verify_natural_language("What is 10 + 10?")

print(result.final_answer)  # 20.0
print(result.status)        # "VERIFIED"
```

## Documentation

Full documentation at: https://github.com/rahuldass19/qwed-open
