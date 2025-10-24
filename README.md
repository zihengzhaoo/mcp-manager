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

```json
{
 "mcpServers": {
   "google-maps-platform-code-assist": {
     "command": "npx",
     "args": ["-y", "@googlemaps/code-assist-mcp@latest"],
      "env": {
              "AMAP_MAPS_API_KEY": "您在高德官网上申请的key"
            }
   }
 }
}
```
