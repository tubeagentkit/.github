# TubeAgentKit

Open-source SDKs, agent tools and automation integrations for getting YouTube transcripts into software. Everything here calls the [GetYouTubeTranscript](https://getyoutubetranscript.com) API, which returns a video's transcript (with optional timestamps), plus search, channel and playlist listings, over plain HTTPS. API reference: [getyoutubetranscript.com/docs](https://getyoutubetranscript.com/docs), OpenAPI spec: [getyoutubetranscript.com/openapi.json](https://getyoutubetranscript.com/openapi.json).

## Which tool do you need?

- **A few transcripts from your own machine:** the free open-source library [jdepoix/youtube-transcript-api](https://github.com/jdepoix/youtube-transcript-api) works well. Libraries like it fetch directly from YouTube, and developers commonly report requests being blocked once code runs from cloud or datacenter IPs.
- **A server, serverless function or agent that needs transcripts reliably:** a hosted API is the usual answer. The packages below wrap ours.
- **An AI assistant (Claude, ChatGPT, Cursor, VS Code):** use the MCP server or the agent skill.

## Packages and integrations

| Use it from | Repo | Install |
|---|---|---|
| Python | [youtube-transcript-api-python](https://github.com/tubeagentkit/youtube-transcript-api-python) | `pip install getyoutubetranscript` |
| JavaScript / TypeScript | [youtube-transcript-api-node](https://github.com/tubeagentkit/youtube-transcript-api-node) | `npm install @tubeagentkit/getyoutubetranscript` |
| Any language (REST, OpenAPI, curl examples) | [youtube-transcript-api](https://github.com/tubeagentkit/youtube-transcript-api) | none, HTTP |
| MCP clients (remote server) | [youtube-mcp](https://github.com/tubeagentkit/youtube-mcp) | `https://getyoutubetranscript.com/api/mcp` |
| Agent skill (Claude Code, Codex and others) | [youtube-transcript-skills](https://github.com/tubeagentkit/youtube-transcript-skills) | `npx skills add tubeagentkit/youtube-transcript-skills --skill youtube-transcript` |
| Cursor | [youtube-transcript-cursor-plugin](https://github.com/tubeagentkit/youtube-transcript-cursor-plugin) | plugin bundle |
| Vercel AI SDK | [ai-sdk-getyoutubetranscript](https://github.com/tubeagentkit/ai-sdk-getyoutubetranscript) | `npm install @tubeagentkit/ai-sdk` |
| LangChain (Python) | [langchain-getyoutubetranscript](https://github.com/tubeagentkit/langchain-getyoutubetranscript) | `pip install langchain-getyoutubetranscript` |
| LangChain (JavaScript) | [langchain-getyoutubetranscript-js](https://github.com/tubeagentkit/langchain-getyoutubetranscript-js) | `npm install @tubeagentkit/langchain-getyoutubetranscript` |
| LlamaIndex | [llama-index-readers-getyoutubetranscript](https://github.com/tubeagentkit/llama-index-readers-getyoutubetranscript) | `pip install llama-index-readers-getyoutubetranscript` |
| Haystack | [getyoutubetranscript-haystack](https://github.com/tubeagentkit/getyoutubetranscript-haystack) | `pip install getyoutubetranscript-haystack` |
| CrewAI | [crewai-getyoutubetranscript](https://github.com/tubeagentkit/crewai-getyoutubetranscript) | `pip install crewai-getyoutubetranscript` |
| `llm` CLI | [llm-getyoutubetranscript](https://github.com/tubeagentkit/llm-getyoutubetranscript) | `llm install llm-getyoutubetranscript` |
| n8n | [n8n-nodes-getyoutubetranscript](https://github.com/tubeagentkit/n8n-nodes-getyoutubetranscript) | `n8n-nodes-getyoutubetranscript` (community node) |
| Activepieces | [activepieces-piece-getyoutubetranscript](https://github.com/tubeagentkit/activepieces-piece-getyoutubetranscript) | `@tubeagentkit/piece-getyoutubetranscript` |
| Dify | [dify-plugin-getyoutubetranscript](https://github.com/tubeagentkit/dify-plugin-getyoutubetranscript) | plugin package |
| Zapier | [zapier-getyoutubetranscript](https://github.com/tubeagentkit/zapier-getyoutubetranscript) | app source |
| Make | [make-getyoutubetranscript](https://github.com/tubeagentkit/make-getyoutubetranscript) | app source |
| Apify | [apify-youtube-transcript-api](https://github.com/tubeagentkit/apify-youtube-transcript-api) | Actor source |

## About

These repositories are maintained by the team behind GetYouTubeTranscript and are MIT licensed. Issues and pull requests are welcome on any of them.
