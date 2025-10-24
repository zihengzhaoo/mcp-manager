1. Install the Gemini CLI
```bash
npm install -g @google/gemini-cli
```
2. Install the Google Maps Platform extension
    * Option 1 - Install Code Assist as a Gemini CLI extension with static preamble, the MCP tool, and basic Google Maps theme:
        ```bash
        gemini extensions install https://github.com/googlemaps/platform-ai.git
        ```
      * Verify the installation by running `gemini mcp list`.
    * Option 2 - Add the MCP server config manually to your `~/.gemini/settings.json` file.

## Sample Prompts
Use these example prompts to get started with the Code Assist MCP server or supported AI agents:
- Show me how to use the Routes API in Node.js.
