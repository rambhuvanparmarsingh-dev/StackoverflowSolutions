## How It Works: 2-Step Intelligent Workflow

```mermaid
graph TD
    A[You Ask AI] --> B{MCP Server}
    B --> C["Securely Query Azure DevOps APIs (WIQL queries + REST API calls)"]
    C --> D[Return Raw Data to AI Agent]
    D --> E[AI Analyzes & Responds]
