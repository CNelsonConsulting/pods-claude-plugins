# Claude Cowork Plugin Library

This repository is a plugin library for Claude's cowork system, organized by user type.

## Structure

- `developers/`: upcoming developer-focused plugin
- `product-manager/`: active plugin (initial implementation)
- `designer/`: upcoming designer-focused plugin

## Current focus

The `product-manager` plugin is scaffolded first and modeled after Anthropic's default knowledge-work plugin patterns:

- `.claude-plugin/` for plugin metadata
- `.mcp.json` for MCP server wiring
- `commands/` for reusable PM task commands
- `skills/` for task-specific operating guidance

## Next steps

1. Customize command prompts to your PM workflows.
2. Tune each skill with your team conventions.
3. Add developer and designer plugins later with the same shape.
