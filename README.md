# MCP Weather Server & Client (Learning Project)

This project demonstrates how a **Model Context Protocol (MCP) server** works and how clients interact with it.

It is built to explore **MCP server-client architecture, async Python, and tool-based workflows**.

---

## 🚀 Features

- MCP Server built with **FastMCP**
- Supports **SSE (HTTP)** and **STDIO (local process)** transports
- Tools:
  - `get_alerts(state: str)` → Fetch real-time weather alerts by US state
  - `get_forecast(latitude: float, longitude: float)` → Fetch weather forecasts
- Async integration with **National Weather Service API**
- Tested running in **Docker** or local Python environment

