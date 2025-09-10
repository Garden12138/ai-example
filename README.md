# ai-example
This is a code example repository that will be used in the process of learning AI

## FastAPI-MCP 运行所需依赖与安装

以下为 `FastAPI-MCP/` 示例运行所需的 Python 依赖（基于当前代码中的导入与官方发布包信息整理）：

- fastapi
- pydantic
- uvicorn
- fastapi-mcp

> 说明：`fastapi-mcp` 自身会带上若干传递依赖（如 `httpx`、`rich`、`pydantic-settings`、`typer`、`mcp` 等），通常无需单独安装；只需安装上述直接依赖即可运行本示例。

### 环境要求
- Python 3.10+

### 使用 pip 安装
```bash
pip install -U fastapi pydantic uvicorn fastapi-mcp
```

### 使用 uv 安装（可选）
```bash
uv pip install -U fastapi pydantic uvicorn fastapi-mcp
```

### 运行示例
在项目根目录执行：
```bash
python FastAPI-MCP/server.py
```
服务器默认启动在 `http://127.0.0.1:8000`，MCP 挂载路径为 `/fastapi-mcp`。
