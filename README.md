<div align="center">
  
# rudof-MCP: ESWC 2026 Reproducibility Materials

</div>

This repository contains the reproducibility materials and obtained results for the paper **"rudof-MCP: A Model Context Protocol Server for Semantic Web Operations"** presented at the **ESWC 2026** (Posters & Demos Track).

---

## Demonstration Link
You can view the full interaction between the AI agent (Claude) and the rudof-MCP server here: [Full Claude Conversation Snapshot](https://claude.ai/share/b94d9818-ef6b-4319-ba72-bb9d4ed295c8)

## Repository Content

### Input Materials (`/input`)
These files were used during the demonstration to showcase the server's capabilities:
* `data.ttl`: The core RDF dataset containing three individuals and their birthplaces.
* `query.sparql`: The federated SPARQL query used to join local data with live population statistics from **Wikidata**.
* `schema.shex` & `shapemap.sm`: The Shape Expressions used for structural validation.
* `schema.ttl`: The SHACL constraints used to demonstrate error detection.

### Obtained Results (`/results`)
> **Note:** Due to Claude platform limitations, the shared Claude conversation snapshot does not render binary image outputs. You can find the actual generated visualization in this folder.

* **`rdf_graph.png`**: The visual representation of the knowledge graph. 
    

## How to Reproduce
1.  **Configure MCP in Claude Desktop**: For detailed step-by-step instructions, please refer to the [official documentation](https://rudof-project.github.io/rudof/cli_usage/mcp.html).
2.  **Execution**: Use the files provided in the `/input` directory to prompt Claude.

---

<div align="center">
  
**WESO, University of Oviedo** | [rudof Project](https://rudof-project.github.io/)

</div>
