# Clayzo for Claude

Author Clayzo animations with Claude and export them as video, GIF or SVG: motion design, product microinteractions and interactive animated components.

After adding the plugin, connect Clayzo from its **Connectors** tab and sign in with your Clayzo account. Claude can then render frames to check its work and export animations with the Clayzo CLI, including in Claude's sandbox.

The skills install the `clayzo` CLI from npm and run it where Claude works. The connector, `https://app.clayzo.com/api/clayzo/mcp`, gives Claude a render pass for your account that lasts an hour. Your animations and exported files are not sent to Clayzo.
