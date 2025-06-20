# mcp-tools-test
[![smithery badge](https://smithery.ai/badge/@Amila-Deshan/mcp-tools-test)](https://smithery.ai/server/@Amila-Deshan/mcp-tools-test)

A simple MCP tools server for testing purposes.

## Features

- Provides some basic tools for arithmetic operations.
- JSON-RPC 2.0 compliant interface.
- TCP/IP or stdio support.
- Easy to extend with additional tools.

## Usage

To run the server:

```bash
node server.js
```

This will start the server on port 9000. You can change the port by modifying the PORT environment variable:

```bash
PORT=3000 node server.js
```

## Available Tools

- `add`: Adds two numbers.
- `subtract`: Subtracts the second number from the first.
- `multiply`: Multiplies two numbers.
- `divide`: Divides the first number by the second.

### JSON-RPC Methods

- `tools/list`: Lists available tools.
- `tools/call`: Invokes a specified tool with provided arguments.

## Installation

### Installing via Smithery

To install mcp-tools-test for Claude Desktop automatically via [Smithery](https://smithery.ai/server/@Amila-Deshan/mcp-tools-test):

```bash
npx -y @smithery/cli install @Amila-Deshan/mcp-tools-test --client claude
```

### Manual Installation

To install the package, clone the repository and run:

```bash
npm install
```

## License

MIT
