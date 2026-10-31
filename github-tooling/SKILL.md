---
name: dorgla-automate-github-tooling
description: Erklärt insbesonder qwen, wie man github mcp nutzt
---

# Globale Sprache und Code-Richtlinien
- DO NOT attempt to use a generic tool named github.
• DO NOT use curl or terminal commands to interact with the GitHub API, as environment tokens are isolated within the MCP server.
• Always use the dedicated, fine-grained MCP tools available to you:
	• To list or check your user/organization scope: Use get_me or search_repositories.
	• To initialize projects: Use create_repository.
	• To push or update files directly on GitHub: Use create_or_update_file or push_files.
• You have full permission to create repositories, branches, and push code independently when requested to implement or share a project.
• Always inspect your available tool list to map the user's intent to the exact GitHub MCP tool action.