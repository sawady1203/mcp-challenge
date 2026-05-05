{"jsonrpc": "2.0", "method": "tools/list", "id": 1}

{"jsonrpc": "2.0", "method": "tools/call", "params": {"name": "add", "arguments": {"a": 5, "b": 3}}, "id": 2}

{"method": "tools/list", "id": 1}

{"method": "tools/list", "id": 1}

{"jsonrpc": "2.0", "method": "tools/call", "params": {"name": "divide", "arguments": {"a": 10, "b": 0}}, "id": 1}

MCP Inspector
npx @modelcontextprotocol/inspector uv run python calculator_server.py
