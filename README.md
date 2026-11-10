# Philip Antoniades

I've worked with MySQL since 1998. These days I build agent and LLM tooling that sits on top of databases, mostly in Python, mostly running on my own hardware in Brooklyn.

## What I'm building

- **[sakila-mcp](https://github.com/pantoniades/sakila-mcp)**: a read-only MySQL server for MCP clients. It has a fail-closed SQL classifier, server-bound parameters, EXPLAIN summaries and structured results an agent can act on.
- **[nunzio](https://github.com/pantoniades/nunzio)**: a local-LLM workout assistant. You log in plain English from the CLI or Telegram, it stores everything in MySQL, and its coaching is grounded in your own history.
- **[unladen-swallm](https://github.com/pantoniades/unladen-swallm)**: benchmarks OpenAI-compatible endpoints (Ollama, vLLM, llama-swap) against frontier models on speed and LLM-judged quality.
- **[sensey](https://github.com/pantoniades/sensey)**: environmental sensor monitoring for Raspberry Pi, with Ecowitt weather station support and MySQL storage.

## Smaller tools

- [paperhat](https://github.com/pantoniades/paperhat): a touch e-paper dashboard for the Pi Zero W, showing NWS weather and live MTA subway arrivals
- [file2db](https://github.com/pantoniades/file2db): loads CSV files into MySQL tables with type inference
- [ocimgr](https://github.com/pantoniades/ocimgr): OCI tenancy inventory and guided bulk cleanup

## What I care about

MySQL internals (InnoDB, binlog, GTID, group replication), safe database access for agents, local inference, and edge devices.

## Elsewhere

Blog: [worldgonemad.com](https://worldgonemad.com)
