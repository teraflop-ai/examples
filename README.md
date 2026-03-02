# Examples

Repository containing example usage of different Teraflop AI APIs.

## Usage

```bash
export TERAFLOPAI_API_KEY="your_api_key_here"
```

## Python

Search Engine API
```python
import os
from teraflopai import TeraflopAI

api_key = os.environ.get("TERAFLOPAI_API_KEY")

url = "https://api.caselaw.teraflopai.com/v1/search/free"

client = TeraflopAI(api_key=api_key, url=url)

results = client.search("City of Houma")

print(results["results"][0])
```