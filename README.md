# Commands

```bash
uv init
uv venv
source .venv/Scripts/activate
uv add arxiv mcp
uv run research_server.py

npx @modelcontextprotocol/inspector

# Prep to deploy to Render
# Render do not support uv; so need to convert to pip
uv pip compile pyproject.toml > requirements.txt
echo "python-3.11.11" > runtime.txt
echo ".venv" > .gitignore
echo ".env" > .gitignore
```
