# mcp-server

MCP Server notes from Coder Consortium

[Tutorial](https://dev.to/debs_obrien/building-your-first-mcp-server-a-beginners-tutorial-5fag)

Totorial says to run the following, but I couldn't get it to work:
```bash
npx -y @modelcontextprotocol/inspector npx -y tsx main.ts 
```


Actual command to run server:
```bash
 npx @modelcontextprotocol/inspector -- npx tsx main.ts
 ```

 Added to `package.json` so you can run 
 ```bash
 npm run instpect
 ```
 as a shortcut

 