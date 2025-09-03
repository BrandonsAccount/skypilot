<h3 align="center"><img src="img/skypilot.png" height="100"></h3>
<!-- https://raw.githubusercontent.com/brandonsaccount/skypilot-vscode-extension/rough-in-skypilot-provider/ -->

## A collection of services for SkyPilot MCP.

SkyPilot (aka SkyPilot MCP) provides loosely coupled, modular services for building AI chat platform.

## GUI <img src="img/gui.png" alt="Alt text" width="50"/>
Your command center for AI interaction. A sleek interface where users can prompt, refine, and iterate with LLMs
without worrying about the plumbing underneath.

[![Open Repo](https://img.shields.io/badge/skypilot--gui-000000?logo=github&logoColor=white)](https://github.com/BrandonsAccount/skypilot-gui)

## VSCode Extension <img src="img/vscodeext.png" alt="Alt text" width="50"/>
Provides a user interface right in the VS Code IDE.

[![Open Repo](https://img.shields.io/badge/skypilot--vscode--extension-000000?logo=github&logoColor=white)](https://github.com/BrandonsAccount/skypilot-vscode-extension)

## Messenger API <img src="img/messenger.png" alt="Alt text" width="50"/>
The courier with authority. Messenger takes prompts, enriches them with context, and delivers them to the right LLM. It’s 
not just message passing, it’s intelligent orchestration. This is the service that ensures your LLMs respond
consistently, securely, and with the right abstractions for downstream systems.

## Thinker API <img src="img/thinker.png" alt="Alt text" width="50"/>
The bridge between SkyPilot Messenger and the LLM models. This service provides separation of duties between the orchestrator /
MCP host and the LLM provider.

## Registry API <img src="img/registry.png" alt="Alt text" width="50"/>
Every system needs a source of truth. The Registry is the control plane for your MCP servers, keeping track of what’s 
available, what’s healthy, and what your ecosystem can call on at any moment.

## MCP Server APIs <img src="img/mcp-servers.png" alt="Alt text" width="50"/>
Our way of letting the Messenger API talk to anything. Lightweight, RESTful interfaces for exposing external services into the 
SkyPilot ecosystem. Add a server, describe its capabilities, and SkyPilot can make it accessible via the Registry API.