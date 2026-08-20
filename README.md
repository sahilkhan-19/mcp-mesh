# 🕸️ MCP Mesh

> A growing mesh of **Model Context Protocol (MCP) servers** connecting AI agents to tools, APIs, databases, and real-world systems.

MCP Mesh is a collection of MCP servers built to explore and experiment with the **Model Context Protocol** and the emerging ecosystem of agentic AI.

Each server is designed around a specific use case — from managing expenses and interacting with databases to connecting AI agents with external services.

---

## 🌌 Why MCP Mesh?

AI models are powerful, but they become far more useful when they can **interact with the world**.

MCP provides a standardized way for AI applications to discover and use external tools and data sources.

**MCP Mesh is my playground for building those connections.**

```text
                    ┌──────────────┐
                    │   AI Agent   │
                    └──────┬───────┘
                           │
                      MCP Protocol
                           │
             ┌─────────────┼─────────────┐
             │             │             │
        ┌────▼────┐   ┌────▼────┐   ┌────▼────┐
        │ Expense │   │ Weather │   │ GitHub  │
        │ Tracker │   │  MCP    │   │   MCP   │
        └─────────┘   └─────────┘   └─────────┘
             │             │             │
           SQLite        APIs        GitHub API
```

---

## 🚀 Servers

| Server                 | Description                                          | Status     |
| ---------------------- | ---------------------------------------------------- | ---------- |
| 💰 **Expense Tracker** | Manage and query personal expenses through MCP tools | 🟢 Active  |
| 🌦️ **Weather**        | —                                                    | 🟡 Planned |
| 🐙 **GitHub**          | —                                                    | 🟡 Planned |
| 🗄️ **Database**       | —                                                    | 🟡 Planned |

> More servers will be added as the mesh grows.

---

## 📁 Repository Structure

```text
mcp-mesh/
│
├── LICENSE
├── README.md
│
├── expense-tracker/
│   ├── README.md
│   ├── main.py
│   ├── pyproject.toml
│   ├── uv.lock
│   │
│   └── src/
│       └── expense_tracker/
│           └── __init__.py
│
├── weather/
│   └── ...
│
└── github/
    └── ...
```

Each MCP server is kept as an independent project so it can have its own dependencies, configuration, documentation, and implementation.

---

## 🛠️ Tech Stack

* 🐍 **Python**
* ⚡ **FastMCP**
* 📦 **uv**
* 🔌 **Model Context Protocol**
* 🗄️ **SQLite / Databases**
* 🤖 **AI Agents & LLMs**

Individual servers may use additional libraries and APIs depending on their purpose.

---

## 💰 Expense Tracker MCP

The first server in the mesh is an **Expense Tracker MCP Server**.

It exposes expense-management functionality to MCP-compatible AI clients, allowing an AI assistant to interact with an expense database through tools.

### Example capabilities

```text
Add expense
List expenses
Search expenses
Calculate spending
Analyze expenses
...
```

More detailed documentation is available inside:

```text
expense-tracker/README.md
```

---

## ⚙️ Getting Started

Clone the repository:

```bash
git clone https://github.com/sahilkhan-19/mcp-mesh.git
cd mcp-mesh
```

Navigate to a server:

```bash
cd expense-tracker
```

Create the environment with `uv`:

```bash
uv sync
```

Run the server:

```bash
uv run main.py
```

> Individual servers may have different setup and execution instructions. Check their respective README files.

---

## 🔌 MCP Clients

These servers are intended to work with MCP-compatible clients such as:

* Claude Desktop
* MCP Inspector
* Other MCP-compatible AI applications

Configuration depends on the individual server and client.

---

## 🧪 Development

This repository is primarily a **builder's playground** for exploring MCP.

Experiments may include:

* Custom MCP tools
* Resources and prompts
* Database integrations
* External APIs
* Authentication
* Agentic workflows
* Tool calling
* MCP client integrations
* Production-ready MCP architectures

Some servers may be experimental, incomplete, or intentionally minimal.

---

## 🗺️ Roadmap

* [x] Build first MCP server
* [x] Integrate database-backed tools
* [ ] Add more practical MCP servers
* [ ] Add comprehensive tests
* [ ] Add Docker support
* [ ] Add CI/CD
* [ ] Improve documentation
* [ ] Publish reusable MCP packages
* [ ] Explore advanced agentic workflows

---

## 📜 License

This project is licensed under the **MIT License**.

See [`LICENSE`](./LICENSE) for details.

---

## 🌌 The Idea

> **One model. Many tools. One mesh.**

MCP is becoming a bridge between intelligent systems and the software they need to interact with.

**MCP Mesh is my attempt to explore that bridge — one server at a time.**

---

<p align="center">
  Built with 🐍 Python, ⚡ FastMCP & a slightly unreasonable amount of curiosity about AI.
</p>
