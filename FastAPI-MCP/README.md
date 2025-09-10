## FastAPI-MCP Required Dependencies and Installation

The following Python dependencies are required to run the example under `FastAPI-MCP/` (based on the imports in this repository and the official package information):

- fastapi
- pydantic
- uvicorn
- fastapi-mcp

> Note: `fastapi-mcp` includes several transitive dependencies (such as `httpx`, `rich`, `pydantic-settings`, `typer`, `mcp`, etc.). You typically do not need to install them separately; installing the direct dependencies above is sufficient for this example.

### Requirements
- Python 3.10+

### Install with pip
```bash
pip install -U fastapi pydantic uvicorn fastapi-mcp
```

### Install with uv (optional)
```bash
uv pip install -U fastapi pydantic uvicorn fastapi-mcp
```

### Run the example
From the project root, execute:
```bash
python FastAPI-MCP/server.py
```
The server starts at `http://127.0.0.1:8000`, and the MCP mount path is `/fastapi-mcp`.
